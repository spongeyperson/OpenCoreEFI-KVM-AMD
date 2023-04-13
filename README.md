> <p align=center> ⚠️ <u><b>Dormant Repository</u></b> ⚠️ </p>
> <p align=center> This repository is at risk of being Unmaintained and therefore Archived, as i do not have time to work on this project on my host system, and this repository has not been updated in quite awhile. Please Refer to <a href="https://github.com/spongeyperson/spongeyperson/blob/main/README.md">spongeyperson/README.md</a> for up to date repositories and more information. I <i>do not</i> provide support for this repo incase anything breaks. <i><b>Use this Repo at your own risk</b></i></p>
<br>

<h2><p align=center>Spongey's MacOS (Monterey) OpenCore EFI for Proxmox</p></h2>
<h6><p align=center>MacOS `12.0.1` using `MacPro7,1` on `Proxmox VE 7.0-13` with Radeon RX 6800XT or GT 710 passed through.</p></h6>

| ![About this Mac](https://user-images.githubusercontent.com/28176188/140259915-6c29e56c-8d9c-4528-a2d2-4e136ff68c74.png) |
| :--: |
| <sub> About this Mac (With AMD Patch Applied) </sub> |

## DISCLAIMER(S)
- __This Repository is currently in a `Work In Progress` State. I am not responsible for your Machine not posting anymore, nor do i provide any support if anything does break. Your results may vary, Use at your own risk__

- __Do not__ use the `config.plist` without first editing the Serial Number & ROM.

## System Specs:
| **Component**    | **Model**                                        |
| ---------------- | ------------------------------------------------ |
| CPU              | AMD Threadripper 2950x 16-Core (`17h`)           |
| CPU Cooler       | NZXT Kraken X62 280mm AIO                        |
| Logic Board      | ASRock X399 Taichi (BIOS 3.92 Beta)              |
| RAM              | 64GB (4 x 16GB) Corsair Vengeance RGB Pro 3600MHz|
| GPU 1            | Powercolor Red Devil RX 6800XT 16GB              |
| GPU 2            | EVGA GT 710 2GB (GK208B Variant)                 |
| OS Disk (NVMe)   | Western Digital SN750 1TB                        |
| PSU              | EVGA SuperNOVA G2 850W 80+ Gold Fully Modular    |
| Case             | Lian Li O11 Dynamic XL-X Black                   |
| Audio Chipset    | ALC-1220                                         |
| Ethernet         | Intel i211                                       |
| Monitor Left     | HP VH240a 23" 1080p                              |
| Monitor Center   | Dell S3219D 32" 1440p                            |
| Monitor Right    | LG E2350 23" 1080p                               |



## What works
- Single GPU passthrough with Hardware Acceleration
- Host CPU Passthrough with OpenCore & [AMD Kernel Patch](https://github.com/AMD-OSX/AMD_Vanilla/tree/master#read-me-first) (Used 16 Core Patch)
- PCIe USB card Passthrough
- On-Board USB Controllers Passthrough
