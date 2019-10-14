# Hackintosh 黑苹果驱动

## 电脑配置

| 规格   | 详细信息                                                     |
| ------ | ------------------------------------------------------------ |
| CPU    | 英特尔i7 7700                                                |
| 主板   | ASUS Z270 AR                                                 |
| 显卡   | 蓝宝石（Sapphire） RX580 8G OC                               |
| 内存   | 金士顿(Kingston) DDR4 2666  台式机内存 骇客神条 Fury雷电系列 (8+8+16 = 32GB) |
| 主硬盘 | 英特尔（Intel） 760P SSD NVMe 250G                           |

## 哪些不能在Clover正常工作

由于没有购置 蓝牙无线网卡 (例如免驱的 `BCM943602CS`  ) ,所以无法测试蓝牙与airdrop是否正常工作,理论上打上驱动是没问题的



## 哪些能在Clover正常工作

暂时用了这么久都能正常工作使用(什么傻* markdown 格式显示不出来...反正 x 就是成功能用的)

- [x] 正常上网 (网线)
- [x] 能休眠,能唤醒,唤醒后无异样(如花屏,断网等)
- [x] 声卡能播放声音(并不是使用万能声卡驱动)
- [x] 能正常关机重启
- [x] 能屏幕保护
- [x] DP口可输出 , HDMI口没试
- [x] 双屏输出
- [x] USB3.0
- [x] 能硬解

![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-10-14-135219.png)

![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-10-14-135243.png)

附上efi与kext(注:Clover自498x版本后调整了文件路径!)

**Drivers**

```shell
ApfsDriverLoader-64.efi
AptioMemoryFix-64.efi
DataHubDxe.efi
FSInject-64.efi
HFSPlus.efi
PartitionDxe-64.efi
VirtualSmc.efi
```



**Kexts:**

```shell
AppleALC.kext
IntelMausiEthernet.kext
Lilu.kext
SMCProcessor.kext
SMCSuperIO.kext
USBInjectAll.kext
VirtualSMC.kext
WhateverGreen.kext
```

