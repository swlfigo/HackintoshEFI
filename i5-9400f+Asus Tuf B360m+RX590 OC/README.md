# Hackintosh 黑苹果驱动

## 电脑配置

| 规格   | 详细信息                                                     |
| ------ | ------------------------------------------------------------ |
| CPU    | 英特尔i5 9400F                                               |
| 主板   | ASUS TUF B360M-PLUS GAMING S  (带S是某东特供版)              |
| 显卡   | 蓝宝石（Sapphire） RX590 8G D5 海外版 OC                     |
| 内存   | 金士顿(Kingston) DDR4 2666 16GB 台式机内存 骇客神条 Fury雷电系列 |
| 主硬盘 | 英特尔（Intel） 760P SSD NVMe 250G                           |
| 次硬盘 | Micron英睿达(Crucial) 500G SSD固态硬盘 SATA3.0接口 MX500系列 |
| 电源   | 航嘉 600w 直出                                               |

## 哪些不能在Clover正常工作

由于没有购置 蓝牙无线网卡 (例如免驱的 `BCM943602CS`  ) ,所以无法测试蓝牙与airdrop是否正常工作,理论上打上驱动是没问题的



## 哪些能在Clover正常工作

暂时用了这么久都能正常工作使用(什么傻* markdown 格式显示不出来...反正 x 就是成功能用的)

- [x] 正常上网 (由于使用的是 USB 外置网卡`EP-AC1606 （8812AU) 需要安装驱动!`, 自己测试过 使用网线也是能上网的,所以驱动正常！)
- [x] 能休眠,能唤醒,唤醒后无异样(如花屏,断网等)
- [x] 声卡能播放声音(并不是使用万能声卡驱动)
- [x] 能正常关机重启
- [x] 能屏幕保护(有点低要求啊....)
- [x] DP口,HDMI口能用
- [x] 双屏输出
- [x] USB口都能用
- [x] 能硬解

![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-09-29-054655.png)



![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-09-29-054735.png)



![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-09-29-054841.png)



![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-09-29-054916.png)



![](http://sylarimage.oss-cn-shenzhen.aliyuncs.com/2019-09-29-054944.png)