# Encoder-ESP8266 Library

This is a fork of the Encoder library from Paul Stoffregen designed to allow it to work using interrupts on an ESP8266 microcontroller (I tested specifically on the WEMOS D1 for my project).  The original library did not work with intterupts on the ESP8266 without an additional ICACHE_RAM_ATTR attached to the interrupt functions to ensure that they are are in IRAM.

----------------------------------------

Encoder counts pulses from quadrature encoded signals, which are commonly available from rotary knobs, motor or shaft sensors and other position sensors. 

http://www.pjrc.com/teensy/td_libs_Encoder.html

http://www.youtube.com/watch?v=2puhIong-cs

![Encoder Knobs Demo](http://www.pjrc.com/teensy/td_libs_Encoder_1.jpg)
