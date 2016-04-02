# css基础

## 盒子模型

在网页中，一个元素占有空间的大小由几大部分构成

* 元素的内容（content）

* 元素的内边距（padding）

* 元素的边框（border）

* 元素的外边距（margin）

这四个部分构成一起构成css的盒模型。

![box](./img/box.jpg)


### 外边距折叠

在CSS中，相邻的两个盒子的外边距可以结合成一个单独的外边距，这种合并外边距的方式被称为折叠。

折叠计算规则：

 1. 两个相邻的外边距都是正数时，折叠结果是它们两者之间较大的值

 2. 两个相邻的外边距都是负数时，折叠结果是两者绝对值的较大值

 3. 两个外边距一正一负时，折叠结果是两者相加的和

