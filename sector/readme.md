
采用css绘制扇形饼图
=================
思路：
-----
+ 首先在一个正方形div内画一个圆（其实是一个相同大小的div，通过border-radius变成圆形）
+ 通过clip属性将正方形的div截去一半，剩下半圆，另一半区域不可见
+ 使用rotate属性将剩下的半圆旋转，即可得到一个扇形
+ 这种方法只能画角度小于180的扇形
+ 将正方形div再次旋转不同角度，即可得到饼图