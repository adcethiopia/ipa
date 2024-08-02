# IPA
Inclusive Pay Africa is being implemented by a consortium led by [Qua-Qua Capital Services](quaquacapitalservices.com). This repository contains hardware design and operating software files, for a low cost portable terminal that will allow various types of financial transactions over mobile network or Wi-Fi channels.
# Getting Started
The operating software is developed using micropython on the ESP-32 microcontroller platform with SIMcom SIM800C GSM and a PN532 based NFC boards. The reference display is a 240x135 lCD module based on the ST7789 display driver chip. A generic 58mm thermal printer supporting a UART interface can be used for receipt printing. Development kits for al of these components are widely available.
# Hardware Componenets
## ESP32 Micropython development boards
A number of boards ESP-32 development boards are available.The ESP32-DevKitC V4 described [here](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/hw-reference/esp32/get-started-devkitc.html#get-started-esp32-devkitc-board-front) is suitable.
The reference design is based on the following components. All these components are popular and widely available as board products that can easily be wired together for development and testing.
## SIM800C
This is a 2G GSM GPRS Quad Band module suitable for IoT use.
## PN532 Module
The PN532 is the most popular NFC chip, that such as read and write to tags and cards.
## ST7789 DisplayModule
This is a 240x135 LCD display that can display 65K colors.
## Thermal Printer
The reference design uses and standard 58mm mini thermal printer available from many suppliers.

Schematics and PCB layouts for a reference design which includes a 3 key touchpad is available in this repository.
