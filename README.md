# [USB](https://github.com/qitas/USB) 

基于STM32F103ZE单片机的播放设备

### qitas@qitas.cn

---

## 描述

针对嵌入式设备和主机间的USB通信，可用于制作上位机控制桌面软件


---


## 组成

####  libusb



####  msvc

vc工程文件

####  android


---

####  win

通过将USB外设生成HID设备，适配windows上位机软件进行通信，也可以生成对应的标准外设

- sscomdll 

一个window下的桌面串口调试软件，需要验证测试

---

####  linux


- libusb 相关的USB驱动源码

- hid设备通信源码

- sscom串口客户端


libusb homepage: http://libusb.info/


---

VCP虚拟串口，通过将USB设备模拟成相应的CDC设备，在上位机上安装相关的驱动，通过通用的串口工具进行通信


STM32 VCP官方驱动：

https://www.st.com/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-utilities/stsw-stm32102.html


---

## 为锻造最美之器

[![sites](qitas/qitas.png)](http://www.qitas.cn)




[![sites](qitas/qitas.png)](http://www.qitas.cn)
