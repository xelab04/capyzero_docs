---
sidebar_position: 1
title: Arduino Nano ESP32
---

Based on the electrical diagram, we also create PCB so you can solder components to make your capibaraZero more stable and portable.

The PCB project files are available [here](https://github.com/CapibaraZero/resources/tree/main/PCB/Arduino_Nano_ESP32/). You will find the EasyEDA project and the gerber file.

You also need to build the Navigation Board, for more information go [here](/docs/pcb/Navigation_Board)

This PCB feature also a TP4057 charging module(LX-LBC3) that includes charging and discharging functionality. It requires a 3.7V lithium battery.

BOM:

- 52Kohm resistor
- 100Kohm resistor
- LX-LBC3 charging/discharging module
- 2-way switch button
- 1 IR Receiver, 1 IR Emitter
- 8 pin female socket
- 15 pin female socket(2pcs.)
- SX1276
- PN532
- SD Card socket
- ST7789 display(1.54 inch)
- Arduino Nano ESP32
- 18650 3.3v battery and 18650 battery socket or a LiPo battery

You can find the case STL [here](https://github.com/CapibaraZero/resources/tree/main/STL/arduino_nano_esp32)