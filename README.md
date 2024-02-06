# Fedora 39 On Orange Pi Zero3 
![Fedora](https://img.shields.io/badge/Fedora-2a4476?style=for-the-badge&logo=fedora&logoColor=white) <img width="28px" src="orangepi.svg"></img>

[ [中文说明](README_zh_CN.md#fedora-39-on-orange-pi-zero3?lang=zh_CN) | [English](#) ]

This image was ported from **Fedora-Minimal-39-20231018.n.0.aarch64**

## Quick Start

1. Download **fedora_39_minimal_orangepi_zero3.7z** and uboot.
   + patch uboot using [ImagePatcher2](https://github.com/lalakii/fedora_39_minimal_orangepizero3/blob/master/ImagePatcher2.exe). (If the memory is 1.5G you can ignore this step), see [YouTube](https://www.youtube.com/watch?v=YLmtxsbvnFM&ab_channel=lalakii)
   + If the memory is 4GB, you may also need to replace certain files, see the u-boot download page for details.
2. Burn *fedora_opi.raw* to sdcard using [Fedora Media Writer](https://fedoraproject.org/workstation/download/).
3. The first time you run ``dnf makecache`` or ``dnf update`` it will be very slow, this is normal.

## Docs

[Fedora Linux 39](https://docs.fedoraproject.org/en-US/releases/f39/)

## Download

+ fedora_39_minimal_orangepi_zero3.7z: [Google Drive](https://drive.google.com/file/d/1R4ikzJ6BJwNWZFmw9r6TP0KXgRufU6nE/view?usp=sharing)
    + ssid: opi-zero3
    + ssh: root@192.168.10.254, the root password is empty
+ orangepizero3_uboot: [Github](https://github.com/leeboby/opizero3-uboot-dtb/)

## Preview

![fedora_39_minimal_orangepizero3_preview](https://raw.githubusercontent.com/lalakii/fedora_39_minimal_orangepizero3/master/fedora_39_minimal_orangepizero3.png)

## License

[fedora-linux-license](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/)
