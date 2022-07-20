# 测试通过型号及编译器版本和测试时间 #

STM32F401CCU6-V6.18-2022.07.21

# 文件来源 #

## Startup ##

使用

	STM32F4xx_DSP_StdPeriph_Lib_V1.9.0\Libraries\CMSIS\Device\ST\STM32F4xx\Source\Templates\arm

中的启动文件。

## CMSIS ##

使用到的文件分别在

    STM32F4xx_DSP_StdPeriph_Lib_V1.9.0\Libraries\CMSIS\Device\ST\STM32F4xx\Source\Templates
	STM32F4xx_DSP_StdPeriph_Lib_V1.9.0\Libraries\CMSIS\Device\ST\STM32F4xx\Include
	STM32F4xx_DSP_StdPeriph_Lib_V1.9.0\Libraries\CMSIS\Include
	Arm\Packs\ARM\CMSIS\5.9.0\CMSIS\Core\Include

## Fwlib ##

使用

	STM32F4xx_DSP_StdPeriph_Lib_V1.9.0\Libraries\STM32F4xx_StdPeriph_Driver

中的库函数文件。

## 注意点 ##

在工程的`CMSIS\inc`中添加`cmsis_gcc.h`方便在VSCode中使用`Keil Assistant`开发。