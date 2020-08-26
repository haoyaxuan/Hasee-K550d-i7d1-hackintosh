# Hasee-k550d-i7d1
## 电脑配置

| 规格     | 详细信息                                            |
| -------- | --------------------------------------------------- |
| 电脑型号 | Hasee-k550d-i7d1                                    |
| 处理器   | 英特尔 酷睿 i7-4710mq 处理器                        |
| 内存     | 三星 DDR3 8GB                                       |
| 硬盘     | 镁光256GB SSD + 1TB HHD                             |
| 集成显卡 | 英特尔图形卡 UHD 620  （无独显）                    |
| 声卡     | 瑞昱 ALC282                                         |
| 网卡     | RealtekRTL8111 + AR5B125（已更换 博通 BCM94360HMB） |
## 适用机型
Hasee-k550d-i7d1（i5/i7均可）。    

## 正常功能：
1：显卡 （核显正常，独显无解）
2：声卡(耳机、蓝牙耳机均正常使用)  
3：hdmi输出 
4：网卡（有线网卡正常，无线网卡无解，换为BCM94360HMB免驱。）  
5：触摸板正常，部分手势可用。  
6：usb全部正常。  
7：电池电量显示正常。  
8：摄像头正常使用  
9：睡眠正常。  
10：变频正常。  
11：支持原生亮度快捷键。  

## 安装教程
1：修改BIOS - Advanced - Intel(VMX) Virtuailzation Technology 为 Disable
2：修改BIOS - Boot - Boot Type 为 Dual Boot Type   

## 注意点
1：买网卡的时候记得买【2根转接线+1根天线】的，这根天线是给蓝牙使用的，否则蓝牙无法信号，搜不到设备。

## 更新日志
- 2020.08.24 全面升级EFI，适配mac os 11并兼容10.14和10.15；摒弃原生声卡，使安装更简单，修复usb3.0问题
- 2020.03.20 修复睡眠后声卡没有声音
- 2020.03.20 修复快捷键调节屏幕亮度，小太阳
- 2020.03.20 修复usb不识别和蓝牙无法使用问题，所有usb扣全部正常识别，但速度只有2.0的速度，蓝牙需要一根天线，插中间的那个端点
- 2020.03.17 修复usb不识别问题，现只有电脑右侧最下面的usb2.0口无法识别
- 2020.03.16 升级到10.15.3，如果想要mac os 10.14.6的请clone后切换10.14.6分支
- 2020.03.16 修复关机再开机后电池状态不在菜单栏显示
- 2020.03.09 修复睡眠后无声音
- 2020.03.08 修复快捷键调节屏幕亮度，小太阳

## 致谢
- [RehabMan](https://github.com/RehabMan) 提供的   [VoodooPS2Controller](https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller)等驱动。    
- [vit9696](https://github.com/vit9696) 提供的 [Lilu](https://github.com/acidanthera/Lilu) ，     [AppleALC](https://github.com/acidanthera/AppleALC)   ，   [WhateverGreen](https://github.com/acidanthera/WhateverGreen)。     
- [Alexandred](https://github.com/alexandred)及其开发团队提供的[VoodooI2C](https://github.com/alexandred/VoodooI2C) 驱动。  
- [Leevast](https://github.com/leo2heaven) 在此特别感谢和我一起制作的小伙伴。

## 联系方式
QQ：3129598

## 觉得资源还不错的可以打赏一下  
| 微信                                                         | 支付宝                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![wechatpay](https://github.com/haoyaxuan/k550di7d1/blob/master/images/wechatpay.png) | ![alipay](https://github.com/haoyaxuan/k550di7d1/blob/master/images/alipay.png) |

