# Adafruit MiniPOV 3.0 (fix)

This is a modified version of the original sources from Adafruit to compile with modern AVR GCC and libc.

Tested with gcc-avr 1:5.4.0+Atmel3.6.1-2build1 and avr-libc 1:2.0.0+Atmel3.6.1-2 on Ubuntu Linux.

## Compiling

* Install `make`, `gcc-avr` and `avr-libc` (on Linux)
* `cd src`
* `make`
* Program with `avrdude` or similar tool

## Links

* [Project documentation](https://learn.adafruit.com/minipov3?view=all)
* [Original source code](http://learn.adafruit.com/system/assets/assets/000/010/177/original/minipovfirmware.zip)
  (The source code does not contain any license or copyright information but it is supplied free of charge since 2005, AFAIK)