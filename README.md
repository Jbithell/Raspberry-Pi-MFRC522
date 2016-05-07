Raspbery Pi RFID Reader
==========

Python script for interfacing the RFID reader plugged into the Raspberry Pi via GPIO

##Requirements
This code requires you to have SPI-Py installed from the following repository:
https://github.com/lthiery/SPI-Py

## Pins

| Name | Pin # | Pin name   |
|------|-------|------------|
| SDA  | 24    | GPIO8      |
| SCK  | 23    | GPIO11     |
| MOSI | 19    | GPIO10     |
| MISO | 21    | GPIO9      |
| IRQ  | None  | None       |
| GND  | Any   | Any Ground |
| RST  | 22    | GPIO25     |
| 3.3V | 1     | 3V3        |
