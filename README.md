
### EPS32-S2 module based 6 Gang 30 Amps Latch Relays in DIN Rail enclosure. Best sutable for secure Home Automation, IOT. 

## Specification 

 - ESP32-S2 Matter ready chipset
 - Embedded IPX to SMA adapter, 3dBi antenna, any SMA Wi-Fi antenna can be used.
 - USB type C programming\debug connector, on board CP2102 USB-TTL converter
 - 6 x 32 Amper Latch Relays, zero current idle consumption, suitable for any type of loads
 - 32A terminals, 10-22AWG, 4mm2
 - 6 x Optocoupled switch inputs
 - 6 x Tact buttons + reset button
 - 2 x  Dallas temperature sensor pins with 5 kilohm pull up resistors
 - 6 x status LED's + 2 status LED's
 - High quality power supply, input voltage 85-305 Volts AC
 -  DIN rail plastic enclosure dimensions 150x106x42mm
 - Board Dimensions 147x87mm

## Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser. 
>[the button  is visible from the 6Gang30AmpsLatchRelayEspHomeReady web page](https://easysensors.github.io/6Gang30AmpsLatchRelayEspHomeReady)

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@8.0.3/dist/web/install-button.js?module"></script>


To tweak the YAML code in 6Gang30AmpsLatchRelay.yaml and burn it into the board 
- follow instructions in the link below and install  ESPHome
[ Installing ESPHome Manually](https://esphome.io/guides/installing_esphome.html)

- compile and upload with command-line: 
 ```esphome run 6Gang30AmpsLatchRelay.yaml```


![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure1.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure11.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure12.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure14.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure15.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure4.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_din_rail_enclosure2.jpg?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_bottom.png?raw=true)
![6 Gang 30Amps Din Rail Latch Relay](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/esp32_relays_top.png?raw=true)


## Pin out:
 
Latch Relays | Latch Relay ESP32-S2 pin #
------------|--------------
Latch Relay 1 ON | 10
Latch Relay 1 OFF | 9
Latch Relay 2 ON | 20
Latch Relay 2 OFF | 3
Latch Relay 3 ON | 19
Latch Relay 3 OFF | 8
Latch Relay 4 ON | 15
Latch Relay 4 OFF | 16
Latch Relay 5 ON | 7
Latch Relay 5 OFF | 6
Latch Relay 6 ON | 5
Latch Relay 6 OFF | 4

Tact buttons |  ESP32-S2 pin #
------------|--------------
Button 1 | 11
Button 2 | 12
Button 3 | 13
Button 4 | 14
Button 5 | 21
Button 6 | 33

Optocoupled switch inputs |ESP32-S2 pin #
------------|--------------
Switch 1 | 34
Switch 2 | 35
Switch 3 | 36
Switch 4 | 37
Switch 5 | 38
Switch 6 | 39

Dallas sensor ESP32-S2 pins: |ESP32-S2 pin #
------------|--------------
Temp 1 | 40
Temp 2 | 41

i2c expander ESP32-S2 (LED's pins): |ESP32-S2 pin #
------------|--------------
SDA | 17
SCL | 18


>[The board schematics Pdf link](https://github.com/EasySensors/6Gang30AmpsLatchRelayEspHomeReady/blob/main/docs/ES%D0%9732_RELAYS_SCH_V1.PDF)
