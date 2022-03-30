# HaarGabelDings

![action shot](https://pbs.twimg.com/media/D5_jCWgWkAEaeBI.jpg)
![render](https://raw.githubusercontent.com/cpresser/haargabeldings/master/doc/render.png)

# Hardware
The current revision uses a SAMD21 MCU, making it compatible with the `Arduino Zero` and the `Adafruit Feather M0 Express`.

Since there was no space left to route tracks or put parts, no other Pins are broken out. Also there is no USB ESD Protection.

## PCB
Export gerbers and order it at you favorite fab.
The first proto used 2mm FR4 instead of the default 1.5mm and is quite usable. Perhaps 3mm is even better.. who knows? One might even try to glue two PCBs together somehow to make the whole thing stiffer.

## Coating?
Some coating is required, otherwise the assembled PCB has to many sharp edges which makes it unusable as a hairpiece. I used epoxy for the prototype. Make sure to mask the switch, debugger-port and USB-connector. You don't want them covered in epoxy (I have been there, don't repeat my mistakes).

## BOM
Nope. I might add one later.

All parts are available at digikey though - assuming there is no global semiconductor supplychain crisis.

## Battery
Connect any single cell lipo battery. I recommend to get one with a build in battery management system.

# Software
The v3 version is supposed to be compatible with the "Adafruit Feather M0 Express", which means one can use micropython.

## USB Bootloader
The Adafruit or Arduino Bootloader should work.
