# 笔记本 Hasee-k550d-i7d1


## 电脑配置
| 规格  | 详细信息     |
| ---- | ----------  |
| CPU | Intel Haswell i7-4710MQ |
| 显卡 | Intel HD Graphics 4600 + NVIDIA GeForce GTX 950M（已屏蔽） |
| 声卡 | ALC282 |
| 网卡 | RealtekRTL8111 + AR5B125（已更换 BCM94360HMB） |
| 硬盘 | 128GSSD + 1THDD |


## 需要操作
- 修改BIOS - Advanced - Intel(VMX) Virtuailzation Technology 为 Disable
- 修改BIOS - Boot - Boot Type 为 Dual Boot Type
- 安装好系统后请将`utility/kexts`内的文件放到`/System/Library/Extensions`，然后适用`kext_utility`重建缓存
- 如果想开启hidpi，请看 [one-key-hidpi](https://github.com/xzhih/one-key-hidpi)，需系统正常后开启，请不要进行EDID注入，只开启hidpi即可

## 注意点
- 本EFI使用了原生声卡驱动，如果不想使用，可以联系作者修改成模拟声卡，原生声卡相比模拟声卡更稳定


## 镜像下载
- 黑果小兵部落阁 [MacOS Mojave 10.14.6 18G87](https://blog.daliansky.net/macOS-Mojave-10.14.6-18G87-Release-version-with-Clover-5033-original-image.html
)，感谢 @黑果小兵


## 已发现问题
1.蓝牙无法使用
2.usb3.0无法正常工作

## 更新日志
- 2020.03.16 升级到10.15.3，如果想要mac os 10.14.6的请clone后切换10.14.6分支
- 2020.03.16 修复关机再开机后电池状态不在菜单栏显示
- 2020.03.09 修复睡眠后无声音
- 2020.03.08 修复快捷键调节屏幕亮度，小太阳


## 作者联系方式
- QQ: 3129598
