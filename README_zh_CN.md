# Fedora 39 On Orange Pi Zero3
![Fedora](https://img.shields.io/badge/Fedora-2a4476?style=for-the-badge&logo=fedora&logoColor=white) <img width="28px" src="orangepi.svg"></img>

[ [English](README.md#fedora-39-on-orange-pi-zero3?lang=en) | [中文说明](#) ]

此镜像移植自: Fedora-Minimal-39-20231018.n.0.aarch64

## 快速开始

1. 下载 **fedora_39_minimal_orangepi_zero3.7z** 以及 uboot文件（1.5G内存的设备，跳到第2步，直接写入镜像）
   + 解压缩镜像文件后, 使用 [ImagePatcher2](https://github.com/lalakii/fedora_39_minimal_orangepizero3/blob/master/ImagePatcher2.exe) 修补镜像的uboot
   + 如果是4GB的设备，可能还需要替换某些文件，具体参考u-boot下载页面的教程
2. 使用 [Fedora Media Writer](https://fedoraproject.org/workstation/download/) 将镜像文件 *fedora_opi.raw* 写入到SD卡，[参考视频](https://www.bilibili.com/video/BV1Zb4y137j3/) 
3. 首次执行 ```dnf makecache``` 或 ```dnf update``` 会非常慢，这是正常现象

## 文档

[Fedora Linux 39](https://docs.fedoraproject.org/en-US/releases/f39/)

## 下载

+ fedora_39_minimal_orangepi_zero3.7z: [谷歌云盘](https://drive.google.com/file/d/1R4ikzJ6BJwNWZFmw9r6TP0KXgRufU6nE/view?usp=sharing) | [蓝奏云](https://a01.lanzout.com/b00xram0d) 密码: 8aih
    + ssid: opi-zero3
    + ssh: root@192.168.10.254, 无密码
+ orangepizero3_uboot: [Github](https://github.com/leeboby/opizero3-uboot-dtb/)

## 预览

![fedora_39_minimal_orangepizero3_preview](https://raw.githubusercontent.com/lalakii/fedora_39_minimal_orangepizero3/master/fedora_39_minimal_orangepizero3.png)

## 许可证

[fedora-linux-license](https://docs.fedoraproject.org/en-US/legal/fedora-linux-license/)