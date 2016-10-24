# ESP8266-ESP12-Adaptor
An adaptor for the ESP-12E/F wifi modules. 

==== Description ====
The ESP8266 chip is an SOC integrating a Tensilca L106 32-bit MCU with 802.11 b/g/n protocol and TCP/IP stacks. The SOC chip is developed by Espressif Systems, a company in Shanghai. AI-Thinker, another Shenzhen-based company provides a series of ready-to-use ESP8266 modules, in which the ESP-12E/F moudle is a compact implementation with on board PCB antena. The ESP-12F module is also approved by the FCC standards.

The ESP12-E/F module, despite its readiness, still needs a bunch of external capacitors and resistors to run. This repository provides a schematic and PCB design for an ESP-12E/F adaptor, including all the external elements and a 3.3V voltage regulator, making the ESP-12E/F module a real ready-to-run module.

==== Features ==== 
* Accepts 3.3V as well as 5V power input.
* The UART of the ESP-12E/F has separate pins with GND and 3.3V power input.
* Has most of the I/O pins of the ESP-12E/F module.

*NOTE: the voltage of the I/O pins are 3.3V, so do not connect the I/O pins directly to devices with 5V I/O voltages.*
