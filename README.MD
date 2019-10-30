# ASUS P8Z68-V LX Hackintosh 黑苹果相关文件
## 简介 
![截图](screenshot/S4000VA.jpg)
这是华硕SandyBridge（英特尔6系列主板)的台式机黑苹果相关文件, 这套配置我仅在苹果10.15.1(macOS Catalina和Mojave)上测试完美 本人自己笔记本每个细节都查阅很多资料进行优化 完美度较高。

:warning: :warning: :warning: 

本项目提供的EFI并不能通用于所有的华硕笔记本，直接覆盖EFI分区可能导致无法启动等问题。推荐了解clover和黑苹果驱动的相关知识后，参考config.plist和驱动修改自己的EFI文件，切勿直接盲目使用。

有问题可以提issue，有时间我会尽可能的提供帮助。 
## 本机硬件
- CPU: intel i7-3770 （原2600 后来咸鱼淘一个3770）
- 内存: 12GB
- 硬盘: SATA 480GB 东芝 SSD
- 网卡/蓝牙：某宝买了一个4天线版黑苹果免驱卡 bios下可用蓝牙键盘和鼠标
- 显卡：1 英特尔HD4000, 2 GTX760 双显卡（但是对随航没啥鸟用需要硬解H.265）
## 哪些可以用？
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI) 独显接4K显示器，集显只能挂2560x1440再高带不动(win下都可带4k)
- [x] 音频ALC887完美注入1，
- [x] HDMI输出
- [x] USB3.0 USB2.0（MultiBeast Mojave把USB3.0相关全钩上即可驱动）
- [x] WIFI/蓝牙(花了268换此网卡后每次升级没卡过网卡)
- [x] 苹果蓝牙键盘
- [x] 苹果妙控鼠标
## 等待修复的问题

- [] 睡眠直接唤醒强刷bios后睡眠无法唤醒 搞不定 只能屏蔽睡眠
- [] 该机貌似不支持从硬盘进行UEFI引导 U盘可以 安装一般我采用Legacy模式

## Asus Laptop 华硕笔记本 hactosh
同为华硕笔记本配置相似y，以下给出友情链接

| 机型名称                          | 发布地址                                                     | 教程地址                                                     | 备注                                                       |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------------- |
| Asus-P8Z68-V-LX-Hackintosh       | [链接](https://github.com/tkrotoff/ASUS-P8Z68-V-LX-Hackintosh) |  |   可参考此人帖子内部有修改后支持UEFI的bios                   |
| Asus P8P67 PRO                   | [链接](https://github.com/rafaelmaeuer/Asus-P8P67Pro-Hackintosh)  | [链接](https://github.com/rafaelmaeuer/Asus-P8P67Pro-Hackintosh/blob/master/readme.md) |   此配置跟此笔记本无关，我台式机配置几乎一样 |
| Asus A411UF                         | [链接](https://github.com/faizauthar12/Asus_A411UF_Hackintosh) |                                                              |   S4000VA的主板型号为X411 配置接近                   |
| Asus ZenBook 系列               | [链接](https://github.com/hieplpvip/Asus-ZENBOOK-HACKINTOSH) | [链接](https://www.tonymacx86.com/threads/guide-Asus-zenbook-using-clover-uefi-hotpatch.257448/) | 华硕笔记本基本换汤不换药一套方案出了很多型号 你懂的  |



####

