# Awesome LILYGO® TTGO T-Watch-2020

> A curated list of resources, examples, documentations, and other things concerning the LILYGO® TTGO T-Watch-2020.'

### Development Platforms

>SP-IDF (native SDK), Arduino, Lua, MicroPython, Scratch

## Product Specifications

### Hardware Specifications

Chipset:ESP32, dual-core MCU, PMU power management \
FLASH:QSPI flash 16MB \
SRAM:520 KB SRAM / PSRAM 8MB \
Button:Power key \
USB to TTL:CP2104 \
On-board clock:40MHz crystal oscillator \
Working voltage:2.7V-3.6V \
Working current \
Sleep current \
Working temperature range:-40℃ ~ +85℃ \
Weight:58.5g \
Display: 1.54 inch LCD capacitive touch screen \
Sensor: BMA423 three-axis accelerometer, built-in step counting algorithm, activity recognition / tracking, advanced gesture recognition. \
RTC clock : PCF8563 

### Power Supply Specifications

Power Supply:Micro USB (5V/1A)\
Charging current:The charging current is programmable and self-adjustable\
Battery：lithium battery

### Wi-Fi Specifications

Standard：FCC/CE-RED/IC/TELEC/KCC/SRRC/NCC\
Protocol：802.11 b/g/n(802.11n，speed up to150Mbps)A-MPDU and A-MSDU polymerization，support 0.4μS Protection interval\
Frequency range：2.4GHz~2.5GHz(2400M~2483.5M)\
Transmit Power：22dBm\
Communication distance：300m

### Bluetooth Specifications

Protocol：meet bluetooth v4.2BR/EDR and BLE standard\
Radio frequency ：with -97dBm sensitivity NZIF receiver Class-1,Class-2&Class-3 emitter AFH\
Audio frequency：CVSD&SBC audio frequency\

### Software specification

Wi-Fi Mode：Station/SoftAP/SoftAP+Station/P2P\
Security mechanism：WPA/WPA2/WPA2-Enterprise/WPS\
Encryption Type：AES/RSA/ECC/SHA\
Firmware upgrade：UART download/OTA（Through network/host to download and write firmware）\
Software Development：Support cloud server development /SDK for user firmware development\
Networking protocol：IPv4、IPv6、SSL、TCP/UDP/HTTP/FTP/MQTT\
User Configuration：AT + Instruction set, cloud server, android/iOSapp\
OS：FreeRTOS

## Downloads

[Arduino Software](https://www.arduino.cc/en/Main/Software)

[Git](https://git-scm.com/downloads)

[Espressif Tools Downloads](https://www.espressif.com/en/support/download/other-tools)

[CP2104 driver](https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip) - Windows 10 should get this automagically, but if not, here it is

## Documentation

[Espressif Documentation](https://www.espressif.com/en/support/documents/technical-documents) - Comprehensive and up to date list of Espressif documentation files

[Espressif Arduino ESP32 Library Git Repository](https://github.com/espressif/arduino-esp32)

[Espressif ESP IDF Git Repository](https://github.com/espressif/esp-idf) - ESP-IDF is the official development framework for the ESP32 and ESP32-S Series SoCs.

[Espressif ESP IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/index.html)

[FreeRTOS](https://www.freertos.org/index.html)

[LVGL](https://lvgl.io/) - LVGL is used in the examples and in the documentation

[LVGL Git Repository](https://github.com/lvgl/lvgl)

[T-Watch-2020](https://t-watch-document-en.readthedocs.io/en/latest/introduction/product/2020.html)

[T-Watch-2020 Git Repository](https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library)


### Component Documentation

[ESP32 Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf) 

[PCF8563 Datasheet](https://www.nxp.com/docs/en/data-sheet/PCF8563.pdf) - Real-time clock/calendar 

[BMA423](https://www.mouser.com/datasheet/2/783/BST-BMA423-DS000-1509600.pdf) - Digital, triaxial acceleration sensor

[ST7789V]() - 1.54" LCD capacitive touch screen

[FT6236U]() - Touch screen chip

[AXP202]() - Power Management Unit

[Max98357a]() - I2S PCM input Class D audio amplifier

[CP2104](https://www.silabs.com/documents/public/data-sheets/cp2104.pdf) - USB-to-UART bridge (?)

## Examples

https://www.instructables.com/id/Lilygo-T-Watch-2020-Arduino-Framework/

## Noteworthy Projects

[whitecatboard/Lua-RTOS-ESP32](https://github.com/whitecatboard/Lua-RTOS-ESP32)

[Getting Started with Lua Language on ESP32](https://iotdesignpro.com/projects/getting-started-with-lua-programming-on-esp32)

[agoodWatch](https://github.com/AlexGoodyear/agoodWatch)

## Noteworthy Links

[How to make use of ESP32 internal RTC to setup Epoch time?](https://github.com/espressif/arduino-esp32/issues/3641)

[LUA language](http://www.lua.org/)

## Images

![](http://ae01.alicdn.com/kf/Ha04278332d4643359779aa8b77f51139K.jpg)

![](http://ae01.alicdn.com/kf/H539aa120ff234ed8b19b2e88f2f42311J.png)

<img src="https://t-watch-document-en.readthedocs.io/en/latest/_images/model41.jpg" alt="drawing" style="width:800px;"/>



