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


## 注意点
- 如果未更换网卡(BCM94360HMB)，请不要将`utility/kexts`内含有Bcm字样的文件放到`/System/Library/Extensions`
- 本EFI使用了原生声卡驱动，如果不想使用，可以联系作者修改成模拟声卡，原生声卡相比模拟声卡更稳定
- 本EFI只适用于 MacOS Mojave 10.14.x 不适用 10.15.x，已测试会无法正常引导 


## 镜像下载
- 黑果小兵部落阁 [MacOS Mojave 10.14.6 18G87](https://blog.daliansky.net/macOS-Mojave-10.14.6-18G87-Release-version-with-Clover-5033-original-image.html
)，感谢 @黑果小兵


## 作者联系方式
- QQ: 3129598
