# avr_splmeter_arduino
Arduino port of avr_splmeter by Davide Gironi (https://davidegironi.blogspot.de/2014/02/a-simple-sound-pressure-level-meter-spl.html)

ported to arduino 1.6.5 by hjgode
using uart library by Peter Fleury

The code compiles for Atmega 328/168 and Atmega8 Optiboot in IDE 1.6.5.

Hardware not yet tested, as missing the microphone and amplifier currently.


# Original README:
==================================================
avr splmeter
==================================================
= Copyright (c) Davide Gironi, 2012              =
= http://davidegironi.blogspot.it/               =
==================================================


A sound level meter or sound meter is an instrument which measures sound pressure
level, commonly used in noise pollution studies for the quantification
of different kinds of noise, especially for industrial, environmental and aircraft noise. 

avr splmeter is a spl meter implementeted on avr microcontroller.
It reads data from an ADC pin and returns the RMS value of the input using
rms avarage method.

Setup parameters are stored in file audioget.h


Devel Notes
-----------
This library was developed on Eclipse, built with avr-gcc on Atmega8 @ 16MHz.
If you include <math.h> add libm library to linker.


License
-------
Please refer to LICENSE file for licensing information.
