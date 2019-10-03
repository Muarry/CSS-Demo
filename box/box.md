# The Box
## 1. box-sizing
该属性控制盒模型以某种方式呈现
- ##### content-box
默认方式，padding和border会添加在盒子内部，盒子内部由三部分组成：（width+padding+border）* 2
- ##### border-box
设置的width和height中已经包括padding和border，可用来设置自适应页面，设置一定的width后，只要padding和border为定值，content的宽高值即可根据总的宽高变化。