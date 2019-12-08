## B365ITX-Hackintosh-OC 华擎B365ITX 黑苹果CLOVER 配置

OC的配置比较复杂现在版本更新也很快还是等更加稳定再上。刚开始折腾OC，想想还是把Clover版本的折腾了一下，毕竟clover还是比较稳定顺手，
顺便把dw1820a给用上了，94360cs2还是给了笔记本用。。。

### 主机配置
- 机箱：某宝（神魔科技)xs1机箱
- 电源：台达 400w 1u 改猫扇 
- 主板：华擎 B365I
- CPU：9900t es
- 显卡：R9 nano
- 网卡：DW1820A
- 内存：DDR4 16g x 2
- 硬盘：东芝RC500 
- CPU风扇：AR11 银欣 

### 正常功能
机型使用 iMAC 19,1 开启了核显加速，目前已99%完美
- 无线网卡：ok
- 蓝牙：ok
- R9显卡：ok
- 核显：ok (核显加速)
- 声卡：ok
- 睡眠/唤醒：ok
- CPU变频：ok

### 安装和问题参考

- 如果使用该EFI进行安装 机型必须设置为iMac 19,1，不能随意更改机型否则usb会失效！

- 可以用小兵最新的10.15.1 镜像进行安装，本EFI集成dw1820a蓝牙驱动，非1820a网卡自行删除相关驱动（Brcm开头的三个kext）

- 处理器类型设置为i9了，因为我es版本的在关于本机显示不正常，其他类型的CPU 可自行去掉cpu类型设置（CPU设置->类型，去掉0x1005）

- 镜像下载：[黑果小兵博客镜像地址](https://blog.daliansky.net/macOS-Catalina-10.15.1-19B88-Release-version-with-Clover-5098-original-image-Double-EFI-Version.html "黑果小兵10.15.1镜像")

- 安装完成建议安装rc.script来模拟nvram，以避免睡眠出现问题，如果用这没问题就忽略吧

- 常见问题：[安装常见问题](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html "安装常见问题")

- Etcher烧录工具：[Etcher烧录工具](https://www.balena.io/etcher/ "Etcher烧录工具")

### 关联OC配置
[华擎B365ITX 黑苹果OC](https://github.com/Good0007/B365ITX-Hackintosh-OC "华擎B365ITX - OC")

