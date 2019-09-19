# [CH645](https://github.com/SoCXin/CH645)

* [WCH](http://www.wch.cn/)：[RISC-V](https://github.com/SoCXin/RISC-V)
* [L1R3](https://github.com/SoCXin/Level): 125 MHz

## [简介](https://github.com/SoCXin/CH645/wiki)

[CH645](https://www.wch.cn/products/CH645.html) 是基于青稞RISC-V内核设计的USB多主机多设备微控制器。内置8组USB高速PHY和2组PD PHY，支持8口USB主机/4口USB设备、PDUSB及Type-C快充功能；内置以太网MAC控制器及100M物理层收发器；内置4通道包括7端口HUB的USB组合设备控制器。提供SDIO、多组定时器、2组USART串口、5个I2C接口、2个SPI接口等丰富外设资源。为PD HUB、KVM、隔离及远距离USB、Type-C扩展坞等应用提供高集成度、易于使用的解决方案。

``` mermaid
gantt
    title CH645 SDK
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.0           :a1, 2024-06-01, 2024-09-30
```

### 关键特性

* 125MHz RISC-V4C，支持RV32IMCB指令集和自扩展指令
* 80KB SRAM + 224KB Flash
* 11路通用DMA控制器
* 多组定时器，包括高级定时器、通用定时器、看门狗定时器以及系统时基定时器
* 2组USART串口：支持LIN和ISO7816
* 5个I2C接口：支持SMBus/PMBus
* 2个SPI接口
* SDIO主机/从机接口：支持EMMC/SD/SDIO卡
* 以太网控制器MAC及10M/100M PHY
* USB2.0高速控制器及PHY，内置8个高速收发器，支持最多8个USB主机和最多4个USB设备
* 内置4通道带HUB的USB组合设备控制器，支持4端口KVM切换器应用
* 基于SerDes的远距离USB收发器PHY，支持USB信号隔离和远距离传输 
* 2组USB PD和Type-C控制器及PHY
* 快速GPIO端口，部分耐受5V，映射16个外部中断
* 封装：QFN68、QFN32

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)
* [mounriver开发环境](http://www.mounriver.com/download)

## [选型建议](https://github.com/SoCXin)

[CH645](https://github.com/SoCXin/CH645) 

