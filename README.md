# PCIE_Arduino
# [· 中文版](README/READMEcn.md)

[![Wechat](https://img.shields.io/badge/-VMA%E7%A1%AC%E4%BB%B6%E7%A4%BE-green?style=flat&logo=Wechat&logoColor=white)](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzI1NDQ4MzIxMg==&scene=124&uin=&key=&devicetype=Windows+10+x64&version=63010043&lang=zh_CN&a8scene=7&fontgear=2)
[![Wechat](https://img.shields.io/badge/-SynthesisDu-green?style=flat&logo=Wechat&logoColor=white)](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzIxODQ0NzQ1OQ==&scene=124&uin=&key=&devicetype=Windows+10+x64&version=63010043&lang=zh_CN&a8scene=7&fontgear=2)
[![Wechat](https://img.shields.io/badge/-SynRGB-05bfdf?style=flat&logo=Bilibili&logoColor=white)](https://space.bilibili.com/62596542)

Arduino on PCIE (not miniPCIE). Achieved by PCIE → RS232/USB → TTL → ATMEGA328P.

Alpha testing, will be update quiet soon.


# A similar project


[Q] What's the difference between [moonpunchorg/pcieduino](https://github.com/moonpunchorg/pcieduino)?
---
[A] Mini-PCIe incorporates USB, while the PCIe does not.
---
![(image load failed)](README/img/mini-PCIE.png)

As the picture shows, mini-PCIE's 36 & 38 pin is USB! The usb control ic is on the mutherboaed.
Instead, PCIE doesn't has this two pin.

For those PCIE to mini-PCIE adapter card, if it wants to maintain the usb function, it will have a external usb cable. At least for me, I haven't saw a usb chip adapt design yet. The reason is obvious, it is not worth to do that.

But as a diy project, I whould like to have a highly integrated design no matter the cost. I want to integration my arduino on a PCIE card and connect with my computer as usual, so I can use this base to make more cool things. Such as a RGB controller. Also this is a good chance for me to practice how to design high speed pcb.


![(image load failed)](README/img/1.png)
![(image load failed)](README/img/2.png)
