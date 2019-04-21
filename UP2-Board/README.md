# Embedded 相关接口
* UART : 2
* USB OTG : 1
* video : 1-HDMI, 1-DP, 1-eDP 40pin.
* audio : 通过 HDMI

# 安装 Clear Linux
参见[[MinnowBoard的内容](https://github.com/shuyong/Learning-Intel-Embedded-Linux/blob/master/MinnowBoard/README.md#%E5%AE%89%E8%A3%85-clear-linux)]。

## 其它
* ttyS0 : 
* ttyS1 : 
* HDMI : 4K LCD 输出。如何播放 4K 视频 ？
* DP : 
* eDP : 

# 安装 Celadon
* Android 8.0 : 能进到主界面。键盘可用，鼠标不可用。
* Android 9.0 : 不能进到主界面，在 android 启动节目就死掉。
* 难道 Intel 的人没有测试过 ？
* 切换到 android-x86.org 。

## Celadon 的分区

# 安装 Zephyr RTOS

# 安装 ACRN

# 安装 ubilinux
* 比较适合用于 Embedded Board。
* 这帮家伙把老版本删除了。除了 Intel 64bit 版本，都没有其它版本了。Intel Edison 的版本也不见了。

## Pinout

[微雪 10 DOF IMU Sensor (D)](http://www.waveshare.net/wiki/10_DOF_IMU_Sensor_(D))
* gpio 在 UP2 Board 平台上的接口是: /dev/i2c-05 or /dev/i2c-06
* 代码写得真烂。要用还得大改。

## MRAA & UPM

# 安装 yocto / IVI / AGL


# 参考文档
1. [UP² Squared](https://wiki.up-community.org/Hardware_Specification_UP2)
1. [Pinout UP2](https://wiki.up-community.org/Pinout_UP2)
1. [Serial console](https://wiki.up-community.org/Serial_console)
1. [UP Board Software](https://wiki.up-community.org/Software)
1. [SerialConsoleHowto](https://help.ubuntu.com/community/SerialConsoleHowto)
1. [Installing Automotive Grade Linux](http://docs.automotivelinux.org/docs/en/master/getting_started/reference/getting-started/machines/intel.html)
1. [Installing Yocto Based](https://wiki.up-community.org/Yocto-based)
1. [UPM sensor library](http://upm.mraa.io/)
