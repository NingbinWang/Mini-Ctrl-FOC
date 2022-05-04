# Mini-Ctrl-FOC
在这个仓库中，主要是设计一个比较小的板子，用于支持2路FOC的电机，通过对于电机的三相电学习以达到驱动的效果，为后续使用无刷电机做基础。

# 硬件设计
硬件设计上，参考使用EG2133作为驱动IC，主要是这个比较便宜，它可以驱动3路电机，对于我的双路电机来讲，绝对是足够的了。


# 软件设计
在软件支持上，除了STM32CubeIDE,还可以支持PlatFormIO,这个具体如何支持可以看[AlientekSample](https://github.com/NingbinWang/AlientekSample), 虽然这个项目已经因硬件停止更新了，但里面的软件VSCODE支持还是可以借鉴的。

## 软件主要功能
* 电机驱动功能（FOC）
* 虚拟USB功能
* OLED显示功能
* RTOS支持
* CAN通信

## 软件版本功能
尚未开始

# 参考
