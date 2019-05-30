# HaarGabelDings

![action shot](https://pbs.twimg.com/media/D5_jCWgWkAEaeBI.jpg)
![render](https://raw.githubusercontent.com/cpresser/haargabeldings/master/doc/render.png)

# Hardware
## PCB
Export gerbers and order it at you favorite fab.
The first proto used 2mm FR4 instead of the default 1.5mm and is quite usable. Perhaps 3mm is even better.. who knows? One might even try to glue two PCBs together somehow to make the whole thing stiffer.

## Coating?
Some coating is required, otherwise the assembled PCB has to many sharp edges which makes it unusable as a hairpiece. I used epoxy for the prototype. Make sure to cover the switch, debugger-port and USB-connector. You don't want them covered in epoxy (I have been there, don't repeat my mistakes).

## BOM
Nope. I might add one later.
All parts are available at digikey though.

## Battery
Connect any single cell lipo battery. I recommend to get one with a build in battery management system.

# Software
Currently its just garbage that requires AtmelStudio.

## USB Bootloader
Yep, that should work. I will try to port https://github.com/majbthrd/SAMDx1-USB-DFU-Bootloader to this hardware.
