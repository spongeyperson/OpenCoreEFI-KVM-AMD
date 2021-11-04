# Spongey's MacOS (Monterey) OpenCore EFI for Proxmox
MacOS Monterey `12.0.1` using `MacPro7,1` SMBIOS on `Proxmox VE 7.0-13` with Radeon RX 6800XT or GT 710 passed through.

| ![About this Mac](https://user-images.githubusercontent.com/28176188/140259915-6c29e56c-8d9c-4528-a2d2-4e136ff68c74.png) |
| :--: |
| <sub> About this Mac (With AMD Patch Applied) </sub> |

## DISCLAIMER
__This Repository is currently in a `Work In Progress` State. I am not responsible for your Machine not posting anymore, nor do i provide any support if anything does break. Your results may vary, Use at your own risk__

## System Specs:
[**CPU**] AMD Threadripper 2950x 16-Core (`17h`)<br />
[**Cooler**] NZXT Kraken X62 280mm AIO <br />
[**Motherboard**] ASRock X399 Taichi (BIOS 3.92 beta) <br />
[**Memory**] Corsair Vengeance RGB Pro 64GB (4x16GB) DDR4-3600 <br />
[**NVME**] Western Digital Black SN750 1TB NVME <br />
[**Graphics Card (Primary)**] Powercolor Red Devil Radeon RX 6800XT 16GB <br />
[**Graphics Card (Alternative)**] EVGA GT 710 2GB (GK208B Variant) <br />
[**Case**] Lian LI O11 Dynamic XL-X Black <br />
[**Power Supply**] EVGA SuperNOVA G2 850W 80+ Gold Fully Modular <br />
[**Monitor Left**] HP VH240a 23" 1080p <br />
[**Monitor Center**] Dell S3219D 32" 1440p <br />
[**Monitor Right**] LG E2350 23" 1080p <br />

## What works
- Single GPU passthrough
- Host CPU Passthrough with OpenCore & [AMD Kernel Patch](https://github.com/AMD-OSX/AMD_Vanilla/tree/master#read-me-first) (Used 16 Core Patch)
- PCIe USB card Passthrough
- On-Board USB Controllers Passthrough
