
# ESPHome Setup for Big Ass Fans: Haiku

This ESPHome configuration has been tested with an older ~2017 Haiku fan using an ESP8285.

The ESP8285 IR boad was purchased from Aliexpress. 

![IR Board](/img/ir-board.png)

This is the remote used to record the IR commands. It may work with other Big Ass Fans brand fans that support IR control. IR codes for all buttons are in [ir-codes.txt](ir-codes.txt).

![Haiku Remote](/img/remote.jpg)



## Hardware
Flashing:

- TTL or FTDI cable
- 5v power source

Install:
- 5v power source
- (Optional) USB micro/C board to power via USB
- (Optional) 3D Printed case

## Installing

### Requirements:

- [Homeassistant](https://home-assistant.io) server
- 2.4GHz Wi-Fi
- TTL/FTDI cable
- Computer capable of installing esptool
  

### ESPHome:

You need to install ESPHome via [getting started guide](https://esphome.io/guides/getting_started_hassio#) if using Hassio.

