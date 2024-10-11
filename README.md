# macOS Sonoma on Lenovo Thinkpad L540 

<details>
<summary><strong>My Hardware</strong></summary>
<br>

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-4300M                 |
| GPU       | Intel HD Graphics 4600               |
| SSD       | Goodram SSD 120GB               |
| Memory    | 16GB DDR3 1600Mhz                     |
| WiFi & BT | Intel Wireless-N 7260                |

</details>  

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth (thanks to [itlwn](https://github.com/OpenIntelWireless/itlwm))
- [X] Brightness / Volume Control 
- [X] Battery Information
- [X] Audio (Apple ALC Speaker)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] DisplayPort
- [X] DVD Drive
- [X] Dock USB / Display
- [X] Handoff / Universal Clipboard
- [X] Sidecar (Cable) / AirPlay to Mac
- [X] SIP / FireVault 2
- [X] Hotkeys via YOGASMC (need to download YogaSMCPane)


</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>

- [ ] Safari DRM ```Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others```
- [ ] Audio Jack (noisy)
- [ ] VGA
- [ ] Sleep with Docking Station
- [ ] Realtek Card Reader ``` it works but shows a warning on statusbar because of unsigned class``` 

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock
- [ ] WWAN

</details>

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

## 📜 License

This repo is licensed under the [MIT License](https://github.com/valnoxy/t440p-oc/blob/main/LICENSE).

The following files are licensed under the [MIT License](https://github.com/valnoxy/t440p-oc/blob/main/LICENSE):
- FixShutdown-USB-SSDT ```(Fixing the Shutdown/Sleep Problems of USB```
- SSDT-ALS0 ```(Fake ambient light sensor)```
- SSDT-ECRW ```(ACPI driver for OEM hardware (YogaSMC))```
- SSDT-HPET ```(IRQ Conflicts fix (Needs _CRS to XCRS Rename))```
- SSDT-PLUG ```(Plugin type to 1 for CPU0/PR00)```
- SSDT-PNLF ```(PNLF device for WhateverGreen)```
- SSDT-THINK ```(ThinkVPC (YogaSMC))```
- UTPMap.kext (USB Mapping for ```MacBookPro11,4```)

OpenCore is licensed under the [BSD 3-Clause License](https://github.com/acidanthera/OpenCorePkg/blob/master/LICENSE.txt).


---
```Copyright (c) 2024 . <muhteremking@gmail.de>```
