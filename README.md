# Thinkpad X1 Extreme Hackintosh OpenCore 9.3.0
English | [简体中文](./README_CN.md)

## Introduction
This is a EFI for Thinkpad X1 Extreme Hackintosh. It based on [zysuper/Thinkpad-X1-extreme-EFI](https://github.com/zysuper/Thinkpad-X1-extreme-EFI), [flymin/Hackintosh-Thinkpad-X1-Extreme](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme) and [sqlsec/CHUWI-COREBOOK-X-I5-8259U](https://github.com/sqlsec/CHUWI-COREBOOK-X-I5-8259U).

Tested on macOS Ventura (13.5) and macOS Monterey (12.6, need to replace AirportItlwm.kext with Monterey version).

## Notice
This EFI is only for Thinkpad X1 Extreme 2019 (Gen 1).

If you want to use this EFI on macOS Monterey, you need to replace [AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm) with Monterey version.

You need to modify the `PlatformInfo` in `config.plist` to make the machine work normally. You can use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/) to generate it.

## Support
- Touchpad & touch screen multi touch
- Red dot PS2 control
- Cpu power management use xcpm & hwp
- Screen brightness adjustment and keyboard button control
- Battery level information
- AppleALC for sound card
- card reader
- Machine sleep and wakeup.
- Intel wireless (itlwm)
- Intel bluetooth
- intel cable Gigabit LAN (mini RJ45)
- intel integrated graphics (iGPU)

## Not support
- NVIDIA GPU (dGPU) and HDMI output