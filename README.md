# Lesson 0：开发环境搭建与验证

使用本仓库提供的 STM32F103 LED 工程，完成环境配置，验证开发环境可用。

## 环境搭建教程

请先阅读[环境搭建教程](docs/环境搭建教程.md)，再完成下面的环境验证。

## 工程与硬件

- 开发板：f103 工控板 V1，STM32F103C8T6。
- 时钟：板载 12MHz 无源晶体，系统时钟 72MHz。
- 指示灯：LED2，PA15，低电平点亮。
- 开发方式：VS Code + Arm Keil Studio Pack（MDK v6）+ Arm Compiler 6，裸机运行。
- 原始工程入口：[lesson01_led.uvprojx](MDK-ARM/lesson01_led.uvprojx)。
- CubeMX 配置：[lesson01_led.ioc](lesson01_led.ioc)。

## 完成要求

- [ ] 配置 Keil Studio 所需的工具、编译器授权和设备支持包，记录实际使用的版本。
- [ ] 将原始 µVision 工程导入为 CMSIS 工程，确认目标芯片、编译器、源文件和内存配置正确。
- [ ] 在 VS Code 中完成一次全量编译，达到 0 错误
- [ ] 学会git使用，魔法上网。Download Zip的打死。
- [ ] 了解编译和调试简略原理，每个文件起到什么作用。
## 实践记录

自行补充环境搭建过程、使用的工具和探针版本、遇到的问题及解决方法，并记录上述各项的实际验证结果。
