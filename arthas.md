# Arthas使用

*Arthas* 是*Alibaba*开源的Java诊断工具，比较好用，具体可以查看[官网](https://alibaba.github.io/arthas/index.html)。使用场景：

- 这个类从哪个 jar 包加载的？为什么会报各种类相关的 Exception？
- 我改的代码为什么没有执行到？难道是我没 commit？分支搞错了？
- 遇到问题无法在线上 debug，难道只能通过加日志再重新发布吗？
- 线上遇到某个用户的数据处理有问题，但线上同样无法 debug，线下无法重现！
- 是否有一个全局视角来查看系统的运行状况？
- 有什么办法可以监控到JVM的实时运行状态？
- 怎么快速定位应用的热点，生成火焰图？

## 一、IDEA使用

安装Alibaba Cloud Toolkit插件，配置好远程服务器。

![image-20200818090807395](https://cdn.jsdelivr.net/gh/lisydata/lisyimages/images/20200818090814.png)

## 二、常用功能

- 控制面板

  `dashboard`

- 线程

  `thread`

  `thread -n 10`

- 反编译

   `jad demo.MathGame`

- 退出

  `stop`