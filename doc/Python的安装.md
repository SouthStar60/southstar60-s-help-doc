# Python的安装
>本文档详细讲述了安装Python的教程，仅适用于Windows。
## 第一步：下载安装包
想要下载Python的安装包有两种方式，进入官网或者进入镜像站。

先来看第一种。

### 官网下载

Python的官网为：[https://www.python.org/](https://www.python.org/)

进入这个链接你会看到如下界面：

![Python官网截图](/doc/images/Python官网截图.png)

接着，将你的鼠标移动到`Downloads`并按下。

![移动鼠标并点击Downloads](/doc/images/在Python官网点击下载.png)

随之，你会进入这个页面：

![Downloads页面](/doc/images/点击Python3.14.3下载Python.png)

你只需要点击`Python 3.14.3`（图中使用红色方框框选区域）就可以开始下载。

![下载后](/doc/images/Python安装包下载后.png)

大部分网络环境都可以从官网下载，但有些情况下，官网下载极其的缓慢，这时候就要用到镜像站了。

### 镜像站下载
镜像站列表

|镜像站名称|地址|
|-|-|
|清华大学开源软件镜像站|https://mirrors.tuna.tsinghua.edu.cn/python/|
|阿里云开源镜像站|https://mirrors.aliyun.com/python-release/|

由于需要镜像站下载的情况较少，所以，这里直接给出地址，不再赘述。

Python3.14.3 amd架构 64位 Windows安装程序[点击此处进行下载](https://mirrors.tuna.tsinghua.edu.cn/python/3.14.3/python-3.14.3-amd64.exe)

Python3.14.3 arm架构 64位 Windows安装程序[点击此处进行下载](https://mirrors.tuna.tsinghua.edu.cn/python/3.14.3/python-3.14.3-arm64.exe)

## 第二步：安装
首先进入你的Python安装包所在目录：

![Python安装包所在目录](/doc/images/进入Python安装包所在目录.png)

双击运行安装程序，会弹出一个窗口：

![Python安装起始页](/doc/images/Python安装程序起始页.png)

我们勾选下方的两个选项，然后点击`Install Now`：

![勾选并安装](/doc/images/勾选Python安装起始页的两个选项.png)

等待Python安装程序走条完成：

![等待安装完成](/doc/images/等待Python安装程序走条完成.png)

显示这个页面就是安装成功了：

![安装完成！](/doc/images/Python安装完成.png)

## 第三步：测试是否安装成功
我们按住`Win键`+`R`，调出运行。

![运行窗口](/doc/images/运行窗口.png)

我们输入`cmd`打开命令提示符。

![命令提示符窗口](/doc/images/命令提示符窗口.png)

输入`Python`按下`Enter↩︎`，然后，命令提示符就会显示类似下面的内容：

```
Microsoft Windows [版本 10.0.19045.6809]
(c) Microsoft Corporation。保留所有权利。

C:\Users\Administrator>python
Python 3.14.3 (tags/v3.14.3:323c59a, Feb  3 2026, 16:04:56) [MSC v.1944 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

这就说明你安装成功了。

恭喜你，你已经成功的安装了Python！

点击[此处](/catalog.md)回到目录页