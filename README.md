
# Hackintosh with ASUS Vivobook 15 M1502YA

Ryzen 7 7730U 8C 16T / 16GB DDR4 3200MHz RAM / AMD Radeon Graphics iGPU (Vega 8)

![image](https://github.com/user-attachments/assets/203e6f39-a880-447c-b722-ece026b56165)

macOS Sequoia, Sonoma and Ventura works fine. I can connect internet with TP-Link Type-C ethernet adapter. 
Disable NootedRed and enable WhateverGreen during installation, after u see desktop, u can reverse these changes.

## What's working

- iGPU graphical acc. (with NootedRed.kext)
- Battery Status
- Sound
- Brightness
- FN keys for control brightness, sound etc.
- USB 2.0 and 3.0 ports
- Touchpad

## What's not working?

- Realtek 8821CE Wireless and Bluetooth (u need to use dongles unluckily)

## What's not checked?
- HDMI Port (idk, i dont have second monitor.)
- Charging from type-c port (i forgot)

## Tested versions

| Version            | Status                                                               |
| ----------------- | ------------------------------------------------------------------ |
| Sequoia 15.3.1 | Working normally |
| Sonoma 14.4 | Working normally |
| Ventura 13.5 | Working normally |

## Version

- Updated to OpenCore 1.0.3, i can't say anything for future updates.
  
