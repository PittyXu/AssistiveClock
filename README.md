Android自学习 {#Title}
==============================

1.介绍
------------------------------

### 1.1 自我介绍

以前也做过Android开发，但个人感觉也就是赶鸭子上架（实习生嘛，没有办法），并没有深入的学习，只是知道一些概念罢了。而且，估计现在对Android的概念也只是停留在了SDK10左右的阶段了。最近正在找工作，比较苦逼，想要重新学习一些Android的概念。我不是大牛，所以写这些东东纯为自己学习，自得一乐，如果有人有兴趣帮助我学习，可以一起来[GitHub](https://github.com/PittyXu/AssistiveClock) Contribute 一下，自然有好工作也不要忘了我。<br/>
首先需要了解一下我想要学习做的事情，自然是想要在项目中提高自己对Android 4.0+的开发能力啦！具体的这个学习项目就是一个叫AssistiveClock的悬浮时钟应用。其实在一年前，我就做过这个项目了，但是个人感觉是没有做好，大家有兴趣也可以去各大应用平台搜“悬浮时钟”应用，Google Play上是找不到的了，因为当时手续比较繁琐就化简为零了。

### 1.2 功能需求
简单叙述一下功能吧:

 1. 时钟
 2. 悬浮窗
 3. 设置
 4. 其他功能

就这点点功能，当然这是主要功能因为是为了学习的，所以会有很多的冗余代码，需要过一遍主要的知识点的嘛~~

2. 设置功能（存储模块）
-----------------------

### 2.1 设计模式

所谓设置，就是将需要的配置信息存储下来(持久化)，并能够保持同步读取。所以这个模块我准备的学习内容是Android的几个存储方式学习。

> - 存储接口设计
> - 工厂模式应用
> - 数据与持久层分离
> - 基本同步应用
> - Android四大存储
