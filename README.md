MFRC522-Pi
==========

Python class for interfacing the MFRC522 RFID module on the Raspberry Pi.

##Info
This class was initially based on https://github.com/mxgxw/MFRC522-python, but the repository was left with some non-working code, and the issues people were having with authentication weren't answered. I therefore fixed the code, added some better functionality, and decided to create my own repository for the project. I don't know which licence the project was released under, but I didn't mean to break any terms by creating this repository.

##Requirements
This code requires you to have SPI-Py installed from the following repository:
https://github.com/lthiery/SPI-Py

##Examples
This repository includes a couple of examples showing how to read, write, and dump data from a chip. They are thoroughly commented, and should be easy to understand.

## Pins
You can use [this](http://i.imgur.com/y7Fnvhq.png) image for reference.

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
