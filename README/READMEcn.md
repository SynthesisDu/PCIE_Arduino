# PCIE_Arduino
# [· English](../README.md)

[![Wechat](https://img.shields.io/badge/-VMA%E7%A1%AC%E4%BB%B6%E7%A4%BE-green?style=flat&logo=Wechat&logoColor=white)](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzI1NDQ4MzIxMg==&scene=124&uin=&key=&devicetype=Windows+10+x64&version=63010043&lang=zh_CN&a8scene=7&fontgear=2)
[![Wechat](https://img.shields.io/badge/-SynthesisDu-green?style=flat&logo=Wechat&logoColor=white)](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzIxODQ0NzQ1OQ==&scene=124&uin=&key=&devicetype=Windows+10+x64&version=63010043&lang=zh_CN&a8scene=7&fontgear=2)
[![Wechat](https://img.shields.io/badge/-SynRGB-05bfdf?style=flat&logo=Bilibili&logoColor=white)](https://space.bilibili.com/62596542)

集成在PCIE卡上的Arduino。与另一个mini-PCIE的arduino的项目有很大不同，还在A测中。


# 有一个类似的项目

[问] 这和 [moonpunchorg/pcieduino](https://github.com/moonpunchorg/pcieduino) 这个项目有什么区别?
---
[答] 区别在于mini-PCIE自带usb，而PCIE没有。
---
![(图片加载失败)](img/mini-PCIE.png)

如图所示,mini-PCIE的36和38脚其实就是usb。这个usb的控制芯片在主板上。
而PCIE并没有这两个usb引脚。

对于市面上能买到的PCIE转mini-PCIE卡，它们都会有一个外接主板9针usb口的线用来在需要时提供usb通道。我们见不到集成usb控制器的转接卡，只有这种外接的方案，原因其实是集成usb芯片毫无性价比可言。

不过对我来说，作为自己设计的项目，就不用在乎成本了。高集成度的优雅是最重要的。同时把Arduino集成在PCIE上之后我还有很多进一步的设计想法。比如制作PCIE槽位的RGB控制器。并且因为有usb与电脑通讯，这些功能都可以开发相应的软件。以及我正好在用这个项目学习高速pcb的设计。





![(图片加载失败)](img/1.png)
![(图片加载失败)](img/2.png)
