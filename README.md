# svg-canvas
study svg and canvas



## 介绍


### SVG介绍

SVG（Scable vector Graphics 可缩放矢量图形）
是一种使用XML来描述2D图形的语言；
因为是基于XML，那么svg DOM中的每一个元素都可以，绑定上javascript事件处理器；
在svg中每一个绘制的图形都被视为对象，svg元素的属性发生变化那么浏览器也会重新渲染图形的。

注意：
1、SVG并不属于html5专有内容，在html5之前就有SVG。

2、SVG文件的扩展名是".svg"。

3、SVG绘制的图像在图片质量不下降的情况下被放大。

4、SVG图像经常在网页中制作小图标和一些动态效果图。

### Canvas介绍

Canvas是通过javascript来绘制2D图像的；
Canvas是逐像素进行渲染的；
在Canvas中一旦图形被绘制完成，它就不会得到浏览器的关注，一旦其位置发生变化，那么整个场景需要重新绘制，包括任何已被该图形覆盖了的图形。

使用
canvas使用javascript在网页上绘制图像，本身并没有绘制能力。
canvas是一个矩形区域可以控制其中的每一个元素。
canvas具有多种绘制路径、圆形、矩形、字符以及图像的方法。
下面是典型的常用的绘图方式。

