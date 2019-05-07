# STM32F103C8T6_CMSIS-DAP_SWO
-----------------------------
基于RadioOperator移植的CMSIS-DAP V2.00修改
https://github.com/RadioOperator/STM32F103C8T6_CMSIS-DAP_SWO

我的改进：    
1、增加SWO_PB7宏定义可以直接使用原来STLINK V2的SWIM口作为SWO。    
2、修改vResetTarget()函数，复位只执行一次。    
3、使用序列号标记硬件版本和SWO引脚（需自己根据实际情况修改）。    
4、更新USB_CM3.lib文件。    
