# Thinkpad X1 Extreme Hackintosh OpenCore 9.3.0
[English](./README.md) | **简体中文**

# 介绍
这是适用于 Thinkpad X1 Extreme Hackintosh 的 EFI。基于[zysuper/Thinkpad-X1-extreme-EFI](https://github.com/zysuper/Thinkpad-X1-extreme-EFI)、[flymin/Hackintosh-Thinkpad-X1-Extreme](https:// github.com/flymin/Hackintosh-Thinkpad-X1-Extreme)和 [sqlsec/CHUWI-COREBOOK-X-I5-8259U](https://github.com/sqlsec/CHUWI-COREBOOK-X-I5-8259U)指针。

已在 macOS Ventura (13.5) 和 macOS Monterey (12.6，需要将 AirportItlwm.kext 替换为 Monterey 版本) 上进行测试。

## 注意事项
此 EFI 仅适用于 Thinkpad X1 Extreme 2019（第 1 代）。

如果您想在 macOS Monterey 上使用此 EFI，则需要将 [AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm) 替换为 Monterey 版本。

在使用此EFI之前，需要修改config.plist中的PlatformInfo才能使机器正常工作。 您可以使用 [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 或 [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/) 来生成它。

## 支持
- 触摸板和触摸屏多点触控
- 小红点
- CPU电源管理
- 屏幕亮度调节和键盘按钮控制
- 电池电量信息
- AppleALC声卡
- 读卡器
- 机器睡眠和唤醒。
- 英特尔无线 (itlwm)
- 英特尔蓝牙
- 英特尔千兆LAN（Mini RJ45接口）
- 英特尔集成显卡（iGPU）

## 不支持
- NVIDIA GPU (dGPU) 和 HDMI 输出