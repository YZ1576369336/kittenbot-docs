# 青蛙手柄驱动安装

针对与Kittenblock中的串口通讯，所以需要提前安装一个串口驱动，如果不安装驱动只能当做一个键盘外设与Kittenblock进行交互（红外功能与3PIN接口无法进行通讯）

## 插上USB

![](./images/c01_01.png)

插好，蜂鸣器会发出一个短曲。证明USB成功枚举(不同电脑枚举的速度不太一样，有些电脑枚举特别快，枚举时间不同属于正常现象)

稳定后，中间的蓝灯常亮，右侧的红色电源灯常亮。硬件为正常

## 安装驱动

实际安装很简单，只是为了手把手让大家跟着做，所以截图比较详细，不要害怕！你可以的！

请对照图片一步步进行操作，不要跳过任何的一步。

### 下载inf驱动配置文件

[下载地址](https://bbs.kittenbot.cn/forum.php?mod=attachment&aid=MjgzOXxhYTgzZjE0MHwxNTU2MDg4MTI4fDN8NTU0)

### 驱动安装选择

右键我的电脑图标——管理——设备管理器

![](./images/c01_20.png)

### 驱动路径选择

![](./images/c01_21.png)

恭喜，安装完成！如果你发现安装不成功，请在再多看仔细看看操作，一般是自己操作有误导致的。


## 如果按照步骤安装依然安装不成功

### 现象

部分电脑照着帖子一步一步操作，装到最后一步的inf，却被提醒以下的情况。

![](./images/c01_23.png)


### 原因

部分电脑是ghost版本，被精简了很多系统文件，所以驱动安装不上。

### 解决方法

用腾讯电脑管家或者驱动精灵类似的软件，检查下电脑有哪些补丁可以更新，都去更新后，就能安装上了
（谢谢小笨老师反馈）

![](./images/c01_24.png)