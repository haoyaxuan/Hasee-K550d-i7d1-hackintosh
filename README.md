# 设备类型: 笔记本
# 品牌: Hasee-k550d-i7-d1
## 芯片组: Intel HM87
## CPU: Intel Haswell 酷睿i7 4710MQ
## GPU: Intel GMA HD 4600（独显已屏蔽）
## 内存：8G
## 硬盘：128GSSD+1THDD
## 声卡：ALC892
## 网卡：BCM94360HMB 或 BCM94352HMB
## 操作系统：MacOS Catalina 10.14.6 + win10 TLSB
## MacOS系统镜像下载地址（感谢黑果小兵提供）：
## https://blog.daliansky.net/macOS-Mojave-10.14.6-18G87-Release-version-with-Clover-5033-original-image.html

# 作者QQ：3129598

# 已知问题：
### 1. usb3.0口插入usb3.0的u盘无法读取，插入2.0的u盘正常
### 2. 重启黑屏，有时候可以进入系统，有时候无限黑屏，关机正常。
# QA
### BIOS设置
### 答：修改 Advanced - Intel(VMX) Virtuailzation Technology 为 Disable 和 Boot - Boot Type 为 Dual Boot Type ，第一个解决电源不充电，第二个是解决开机8个苹果。 

