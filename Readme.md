### OpenCore with Monsterey for Ausu TUF B560M-E + i9 11900 (es) QVYE + RX5500XT



原EFI基于pcbeta吧友[shedanqin](https://i.pcbeta.com/space-uid-4457996.html)制作，原帖地址：https://bbs.pcbeta.com/viewthread-1930522-1-1.html

OpenCore 0.7.8

Monsterey 12.1 dmg 安装包取自黑果小兵

原帖链接：https://blog.daliansky.net/macOS-Monterey-12.1-21C52-Release-version-with-OC-0.7.6-CLOVER-5143-and-FirPE-original-image.html

下载链接：[https://mirrors.dtops.cc/ISO/MacOS/macOS Monterey 12.1 21C52 Installer for CLOVER 5143 and FirPE.dmg](https://mirrors.dtops.cc/ISO/MacOS/macOS Monterey 12.1 21C52 Installer for CLOVER 5143 and FirPE.dmg
)

主板: Ausu TUF B560M-E 无wifi，因此在原版基础上禁用了无线相关驱动，添加agdpmod=pikera 解决显卡黑屏问题。



v0.1:

休眠，键盘唤醒，CPU在低负载时不发烫，有线网络ok。

v0.2:

* 暂时禁用CPUFriend, 可能导致cpu偶尔死机.
* 添加USBmap,并且注入电源属性,支持iphone/ipad 2.1A快充.



在此之外，尝试过一些收费方案，但都卡死在第二安装阶段，“At least 25 minuits ....”，具体原因暂时未查明。

https://macx.top/24431.html

https://macx.top/20591.html

