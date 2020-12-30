# BareMetal_STM32L0_BLEuart

This FreeRTOS programs uses C programming language that enables the STM32 mcu to get the BLE readings from the ESP32 through UART communication channel.

ESP32 BLE functon is eing wake up thrugh UART by initiating the AT command

Next, the scanning command invoked (AT+SCAN)

The BLEchck would store the response received from ESP32 BLE which would be visible throug debugger.

## Requirements

 **1 STM32L0**
  
 **2 ESP32**
  
 **3 STM32CUBEMX**
  
 **4 Keil/Eclipse  (I'm using Keil)**


## How to use this
You need to build the project using stm32cubemx software.
I had provided the .ioc file for this purpose

Utilize the Inc and Src files.
