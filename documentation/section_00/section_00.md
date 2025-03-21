### Hardware Modules

The following modules can be assembled on a prototype board or breadboard to develop a system, before a custom PCB is produced. Some soldering skill will probably be required. 

| Description                                               | Sample Image                                                 |
| --------------------------------------------------------- | ------------------------------------------------------------ |
| Espressif ESP32 DevKitC microcontroller development board | ![esp32_devkitc](esp32_devkitc.png)   |
| SIM800L GPRS module                                       | ![sim800l](sim800l.png)               |
| ST7789 display module                                     | ![st7789_module](st7789_module.png)   |
| Pushbutton switches                                       | ![push_button_swith](push_button_swith.png) |
| 5V DC-DC converter (needed to drive a thermal printer)    | ![power-module](power-module.png)     |
| Thermal printer module with TTL serial interface          | ![thermal_printer_module](thermal_printer_module.png) |
| Lithium battery 3.7V                                      | ![lithium_battery](lithium_battery.png) |

### Schematics

The schematics show how the components should be wired together, in order to run the example code in the last section. 

#### Power Module

![dc_dc_converter](dc_dc_converter.png)

#### Display and Keypad

![esp32_display_keypad](esp32_display_keypad.png)

#### GPRS Module

![esp32_devkit_sim800](esp32_devkit_sim800.png)

#### Thermal Printer

![esp32_thermal_printer](esp32_thermal_printer.png)

