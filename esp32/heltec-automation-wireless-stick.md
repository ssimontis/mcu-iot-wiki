# Heltec Automation Wireless Stick

### Basic Specs

* ESP32 CPU
  * Dual-core 32-bit MCU + ULP core
  * LoRa node chip SX1276/1278
* MicroUSB interface
  * Voltage regulator
  * ESD & short circuit protection
  * RF shielding
* SH1.25-2 battery interface onboard
  * Integrated lithium battery management system
  * Charge and discharge management
  * Overcharge protection
  * Battery Power Protection
  * USB/battery power automatic switching
* Integrated WiFi, LoRa, Bluetooth connections
  * Onboard Wi-Fi
  * Bluetooth dedicated 2.4GHz metal 3D antenna
  * Reserved IPEX \(U.FL\) interface for LoRa use
* 0.49 inch 64\*32 dot matrix OLED display
  * Available for debugging info, battery power readings, etc
* Integrated CP2102 USB to serial port chip for program downloading, debugging info
* Arduino environment support
* Supports Arduino version of ESP32 + LoRaWAN protocol routine provided by Heltec
  * Can communicate with any gateway or base station running LoRaWAN protocol
  * Requires unique license

### Technical Parameters

* MCU: 240MHz Tensilica LX6 dual-core + 1 IULP
  * 600 DMIPS
* 520 KB SRAM
* Dual mode Bluetooth
* SX1276 LoRa Chip
  * US\_902\_928 LoRa band support
  * Maximum Output: 18 dB +/ 2 dB
* Interfaces
  * 3x UART
  * 2x SPI
  * 2x I2C
  * 1x I2S
* HW Resources
  * 12-bit ADC, 8-bit DAC
  * 29 GPIO
* 4MB \(32M-bits\) SPI FLASH
* Micro USB x1
* LoRa antenna interface \(IPEX\) x 1
* USB to UART Bridge: CP2102
* 3.7V Lithium battery accepted \(SH1.25x2\)
* Deep sleep 800 uA

### Electrical Characteristics

| Electrical Characteristics | Condition | Minimum | Typical | Maximum |
| :--- | :--- | :--- | :--- | :--- |
|  | USB Powered \(&gt;= 500mA\) | 4.7V | 5V | 6V |
|  | Lithium Powered \(&gt;= 250mA\) | 3.3V | 3.7V | 4.2V |
| Power Supply | 3.3V pin powered &gt;= 150mA | 2.7V | 3.3V | 3.5V |
|  | 5V \(pin\) powered &gt;= 500mA | 4.7V | 5V | 6V |
|  | WiFi scan |  | 115mA |  |
|  | WiFi AP |  | 135mA |  |
| Power Consumption \(mA\) | LoRa 10dB |  | 50mA |  |
|  | LoRa 12dB |  | 60mA |  |
|  | LoRa 15dB |  | 110mA |  |
|  | LoRa 20dB |  | 130mA |  |
|  | 3.3V pin output |  |  | 500mA |
| Output | 5V pin \(USB\) |  | Equal to input current |  |
|  | External device power control \(Vext 3.3V\) |  |  | 350mA |

* Supports LoRaWAN protocol V1.0.2 Class A and C
* Uses ESP32 internal RTC \(15KHz\)
* Supports deep sleep and stop mode with multiple cycle wakeup
* Receive and print downlink payload
* Print and OLED show downlink data length and the RSSI
* Unique license related to Chip ID required, [check license](https://www.heltec.cn/search)





