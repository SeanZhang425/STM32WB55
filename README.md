# **STM32WB55 Bluetooth Firmware**

Firmware for a custom STM32WB55CEU6 microcontroller I designed, developed using STM32 CubeIDE, to enable BLE communication. Find out more about the project [here](https://www.notion.so/sean-zhang/Sean-Zhang-Aspiring-Computer-Engineer-1805d3c7d8a6801292f7ced387f20249?p=1b15d3c7d8a6802c8c51e6af6f418733&pm=c).

## **Overview**  
This firmware initializes and tests Bluetooth functionality, allowing the microcontroller to receive a single character from a mobile device over BLE. This verifies that the Bluetooth stack is properly set up and that basic communication works.  

## **Features**  
- BLE communication using the STM32WB55’s integrated wireless stack  
- Receives a single character for initial testing  
- Developed with STM32 CubeIDE  

## **Getting Started**  
### **Prerequisites**  
- Custom STM32WB55 MCU
- STM32 CubeIDE (latest version)  
- STM32CubeWB firmware package  
- BLE testing app (e.g. STBLEToolbox)  

### **Setup**  
1. Clone this repository.  
2. Open the project in STM32 CubeIDE.  
3. Compile and flash the firmware.  
4. Connect to the STM32WB55 over BLE and send a single character to test.
