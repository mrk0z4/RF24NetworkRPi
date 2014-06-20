RF24NetworkRPi
==============

An implementation of RF24Network for Raspberry Pi.

This is based on the library for Arduino from https://github.com/maniacbug/RF24Network and https://github.com/maniacbug/RF24/, so everything needed to operate with nRF24L01+ modules is already included.

Because I found nothing regarding this library for Raspberry Pi, except for one fork (but it didn't satisfied me and the developer was inactive), I started to translate those minor details that prevented the library to run on the Raspberry Pi.

Anyway, my efforts turned my goal into reality.

Instructions:

	0. Be sure you have the nRF24L01+ module connected to the SPI pins (CE is physical pin 25).
	1. Navigate into RF24NetworkRPi directory.
	2. On the console, write the command "make". Then "sudo make install".
	3. To run any example, e.g. meshping, navigate to that directory and do "make".
	4. Run the program with "sudo ./meshping"
	5. Enjoy. Now you can do a mesh network using this module inside your house.

==============

I've ported only the meshping example, but I plan to port the others ASAP.

If you have a problem regarding this library, please report it. At my free time, I'll give it a look.
