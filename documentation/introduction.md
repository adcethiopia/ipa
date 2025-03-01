# Getting Started
The development of a system can be started by putting together the different hardware modules on a prototype or breadboard, and loading the software in this repository on to the microcontroller module (in the case of this reference platform an ESP32 DevkitC). The microcontroller can be accessed using terminal software on a PC. The sections in this directory describe this process.

[Hardware Modules](https://github.com/adcethiopia/ipa/blob/main/documentation/section_00/section_00.md)

[Preparing the ESP32 DevKitC and Development Environment](https://github.com/adcethiopia/ipa/blob/main/documentation/section_01/section_01.md)

[Using the REPL](https://github.com/adcethiopia/ipa/blob/main/documentation/section_01/section_02.md)

[Example Code Snippets](https://github.com/adcethiopia/ipa/blob/main/documentation/section_01/section_03.md)

The links below can be used as further references to aid in this process.

## Hardware Components
### ESP32 Micropython development boards
A number of boards ESP-32 development boards are available. The ESP32-DevKitC V4 described [here](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/index.html) is suitable.

## Software
### Getting Micropython
Instructions for obtaining and flashing Micropython for the ESP32 can be found [here](https://docs.micropython.org/en/latest/esp32/tutorial/intro.html).
### Uploading Modules
* A list of tools that can be used to develop and upload modules can be found [here](https://randomnerdtutorials.com/micropython-ides-esp32-esp8266/).
* Instructions for using the command line Adafruit Micropython Tool ampy can be found [here](https://pypi.org/project/adafruit-ampy/).
* Instructions on using the Thonny development environment can be found [here](https://randomnerdtutorials.com/getting-started-thonny-micropython-python-ide-esp32-esp8266/).
### Using the Micropython REPL
The Micropython REPL (Read Evaluate Print Loop) is a useful tool for learning Micropython and for developing and testing modules. A free tool that can be used for this, available for PCs running both Windows and Linux is [putty](https://www.putty.org/). Downloads are can be found [here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html). A short introduction on how to use MicroPython from the REPL can be found [here](https://docs.micropython.org/en/latest/esp8266/tutorial/repl.html). Micropython documentation including tutorials for different platforms can be found [here](https://docs.micropython.org/en/latest/index.html).
## Running in a Production Setting
### Flash Encryption
The Flash Encryption feature of the ESP32 allows encryption of the contents of the off chip flash memory. This means that the contents will not be accessible by means of a direct connection to the controller. This way certain information like passwords and keys only readable by the application can be stored. The procedure to do this can be found [here](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/security/flash-encryption.html).

