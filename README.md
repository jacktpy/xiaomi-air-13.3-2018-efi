# 适用于小米笔记本Air 13.3" 2018的EFI文件

## 支持的MacOS版本：

* macOS 10.13 High Sierra
* macOS 10.14 Mojave
* macOS 10.15 Catalina
* macOS 11.00 Big Sur
* macOS 12.00 Monterey

  # 哪些东西工作正常？

- 原生CPU电源管理

- 睡眠/唤醒

- Intel核芯显卡

- 音频（使用AppleALC）

- 触控板（包括手势）

- HDMI音频和视频

- USB 3.0

- NVMe/SATA 固态硬盘

- 电池管理

- 亮度调节

- 内置摄像头

- 内置麦克风

- 文件保险箱加密（使用这项功能前一定要备份你的文件！！）
- Intel Wifi 网卡

  ## 未完美工作

- Intel 蓝牙 部分设备可用（没有Airdrop，AirPods Pro正常，罗技Master 3鼠标无法连接）

  ## 不工作

- Nvidia GPU (MX150/GP108) (在macOS下不支持并很可能永远不会支持)

- 指纹传感器（在未来或许使用libfprint）
