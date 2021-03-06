# 截图拍照与显示

既然我们的AI模块有摄像头，那么我们能不能做成类似拍照功能，把图片保存下载来呢？答案当然，可以，而且还能进行图片浏览。



## 装上内存卡

截图是保存在内存卡上，因此必须插上。内存卡最大支持16G，存储卡推荐主流品牌，否则会有不识别的现象。

![](KOI07/01.png)



## Robotbit硬件接线

这里以Robotbit为例，当然你也可以用Powerbrick，Powerbrick接线会更简单些，而且不会接反。

电源正负极切勿接反！

电源正负极切勿接反！

电源正负极切勿接反！



接线附图所示，请再三确认后！再打开电源！

![](KOI10/01.png)



## 打开Robotbit电源

打开电源后，锦鲤魔块就会亮起来

![](KOI10/02.png)

![](KOI10/03.png)







## 编写拍照截图程序

请自行加载

KOI的插件：https://github.com/KittenBot/pxt-koi



编写程序：

![](KOI07/03.png)



## 程序结果

- 把程序下载到Microbit上

- 按下Microbit的按键A，即可“拍照”
- 按下Microbit的按键B，即可显示刚才拍的图片



## 改进程序——连续拍照

上面的程序是拍照一次后就会覆盖，只能保存一张照片，不符合真实使用场景。

因此这里引入变量，用于以序号形式保存照片，可以保存多张照片

![](KOI07/02.png)

校准成功后，可以看到颜色已经可以进行追踪了。



## 常用问题和解答

1、为什么我重新打开电源，按按键A，为什么没有反应？

答：

KOI鲤鱼魔块初始化启动是需要时间，明显比Microbit慢。Microbit的初始化程序已经跑完了，KOI还没初始化。因此按按键A没有反应

**解决办法：**打开电源后，等待KOI屏幕启动完毕后。重新按下Microbit背后的Reset按键，让Microbit重新开始运行（秘诀即让KOI魔块先运行起来，再让Microbit进行运行）。



2、显示图片时，屏幕下方是黑色，且有噪点，是屏幕坏了吗？

答：

不是的，模块截图保存实质摄像头中的数据，所谓摄像头的数据就是照片，照片应该是矩形，而不是正方形，因此模块屏幕显示下发必然有黑色条条。






