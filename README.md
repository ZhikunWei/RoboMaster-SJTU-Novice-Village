
# 上海交通大学-交龙战队/自由度机器人-新人coder学习路线<br>
**说明：此文档仅提供针对新手coder的学习路线，不包含详细教程，请[百度](www.baidu.com)/[Google](www.google.com)自己遇到的问题，能搜到的问题就不是问题，学会在[CSDN]/[StackOverflow]等等鱼龙混杂的博客中求生存是coder的第一课**<br>

PS: 如果需要科学上网，推荐工具 [蓝灯/lantern](https://github.com/getlantern/download)，免费版每月500M流量，(北京开大会的时候可能会暂停)。如果想购买专业版，请务必输入我的邀请码296G9N，谢谢
## 1 Linux
我们一般使用ubuntu操作系统，ubuntu是基于linux的免费开源桌面PC操作系统，操作简单，界面友好。你可以选择安装虚拟机或者安装双系统，如果是第一次接触linux的话就先安装虚拟机。如果是计算机相关专业，在不久的将来就会遇到要使用Linux的课程。

### 1.1 ubuntu虚拟机
新手推荐先使用虚拟机，推荐虚拟机软件为VMware Workstation, 交大为学生提供[免费授权的VMAP系列软件](http://vmap.sjtu.edu.cn/) ，简单申请之后便可以免费使用最新版的Vmware Workstation pro 15 (绿色的那个)<br>
创建虚拟机需要操作系统镜像文件，ubuntu镜像文件下载 [Ubuntu Desktop 18.04](https://www.ubuntu.com/download/desktop)<br>

### 1.2 ubuntu/window双系统
有一定了解之后，可以选择在自己的电脑上安装ubuntu/window双系统，[Ubuntu官方安装教程](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows?_ga=2.147366260.2141779721.1542328276-1363744011.1542328276#0). PS:有一定几率搞崩电脑，建议先备份全硬盘的重要文件<br>

### 1.3 初识Ubuntu
ubuntu[中文入门指南](https://wiki.ubuntu.com.cn/Ubuntu%E6%A1%8C%E9%9D%A2%E5%85%A5%E9%97%A8%E6%8C%87%E5%8D%97)<br>

### 主线任务（ubuntu）：安装好ubuntu18.04。可选任务：安装windows/ubuntu 双系统

## 2 C++
C++是一门非常常用的编程语言，几乎是一名coder必学科目，C++博大精深，“精通C++”无疑是coder最装bi的自我介绍。

### 2.1 IDE和编译器
新手刚接触C++推荐的IDE，[codeblocks](http://www.codeblocks.org/downloads)，可用于日常小代码编写，如做OJ题目、编程小作业。如果需要在windows下安装C++编译器，[在这里](http://www.mingw-w64.org/doku.php/download) <br>
进阶推荐——Clion，交大提供jetbrain全套正版授权软件，下载安装[JetBrains All in One](http://lic.si.sjtu.edu.cn/Softs/good/id/1625)，
其中包括Clion. 使用这个软件需要学习使用[cmake](https://www.cnblogs.com/cv-pr/p/6206921.html), 推荐在Linux中使用，适合较大型工程代码编写<br>
ps:这个软件还包括jetbrain为其他语言开发的IDE，如pycharm适用python，idea适用java，还有很多其他的。<br>


### 2.1 初识C++
C++从头学起，[C++新手村教程](http://www.runoob.com/cplusplus/cpp-tutorial.html)，应掌握基本语句、函数调用、引用参数传递方式、类等内容。

### 2.2 C++算法实战
了解一定C++基础之后，应当学习一些算法，交大有一个代码在线[评测网站](https://acm.sjtu.edu.cn/OnlineJudge/problems)，
其中提供了非常多难易不等的题目，它的题目列表可以按照提交通过率排序，推荐新手从通过率高的题目做起<br>

### 支线任务（一）- 仅针对C++无基础或弱基础同学 <br>
  在交大OJ上完成任意10道题

### 2.3 opencv
[安装教程](https://docs.opencv.org/master/d7/d9f/tutorial_linux_install.html)，安装3.3.0及其以上版本，不要安装4版本

### 主线任务（opencv）：配置好opencv

## 3 摄像头使用
示例代码：[摄像头使用](https://github.com/ZhikunWei/SJTU_VISION_GROUP)，里面的注意事项txt提供了一些常见错误的解决办法。<br>
相机驱动[下载](https://github.com/ZhikunWei/SJTU_VISION_GROUP/tree/master/%E7%9B%B8%E6%9C%BA%E9%A9%B1%E5%8A%A8)，自己电脑上的选pc文件夹下的文件。
相机在C楼105，要使用时联系我或直接前往

### 任务（单摄像头） 单摄像头使用 <br>
任务目标：在电脑上显示摄像头画面，并录制一段视频文件

### 任务（双摄像头）双摄像头使用 <br>
任务目标：在电脑上显示双摄像头画面，并录制视频文件


## 待续
