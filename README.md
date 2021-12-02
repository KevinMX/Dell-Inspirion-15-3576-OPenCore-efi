# Dell-Inspirion-15-3576-OpenCore-EFI

### Notice: I'm not using this and probably NOT gonna touch ANY Apple, Inc products in the near future, so I'm not actively maintaining this repo. Hence I'm not responsible for any potential damage to your own hardware. Use it at you own risk, good luck and have fun.

EFI for Dell Inspiron 15-3576

CPU: Intel Core i5-8250U

RAM: DDR4 SODIMM (dual slots up to DDR4-2400, tested with 16G*2 sticks)

iGPU: Intel UHD Graphics 620 (Working)

dGPU: AMD Radeon 520 (Not working, probably incompatible with macOS, disabled)

Wireless/BT: Qualcomm QCA9377 (Incompatible, replaced with Intel AX200)

You will need [Heliport](https://github.com/OpenIntelWireless/HeliPort) to get WiFi working on AX200. Or, use airportitlwm instead.

Audio: Realtek ALC236 (Working)

USB 2.0/3.0: Working

SD Card Reader: Realtek/USB 2.0 (Not working)

Brightness Control: Working but not via keyboard shortcut (Fn+F11/F12), you'll need to change it in system settings. More works needed.

Touchpad: Working

Tested on macOS Big Sur 11.5.1.

![截屏2021-08-09 下午8 05 08](https://user-images.githubusercontent.com/17025286/128703451-72a19c20-6762-4839-ac70-30c6995eee71.png)

Massive thanks to [sjllls](https://github.com/sjllls) and [zsakvo](https://github.com/zsakvo) for helping.
