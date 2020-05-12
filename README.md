# keil调试stm32，jlink报错

## 1.报错
在使用新版MDK调试stm32或者是其他的arm芯片的时候，由于我用的是jlink ob的克隆版本，经常会弹出the connected jlink is defective 错误。
![](http://image.skywang.fun/picGO/20200512214314.jpg)之前给的教程4.9的dll替换最新的驱动，这种方法我在5.26中测试已经失效。
## 2.解决
我用从keil5.11 提取出来的dll驱动覆盖到最新版的安装路径（比如D:\Keil_v5\ARM\Segger），亲测效果很完美。
![](http://image.skywang.fun/picGO/20200512215005.png)
