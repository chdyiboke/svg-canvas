# canvas 的行内属性width、height与css的width区别

## canvas的绘制会是画布大小为准的
<!-- 画布大小 -->
<canvas id="myCanvas" width="200px" height="100px" style="border:1px solid #333">

<!-- 容器大小 -->
<canvas id="myCanvas" style="width:100px;height:100px;border:1px solid #333"></canvas>

如上：容器变小，精度变小，画会等比例缩小。


`设置画布大小后，样式会重置。`

