Use the edited LMCI library for 915Mhz connect to ttn
=====================================================

*Original reference from the LMCI library:

https://github.com/matthijskooijman/arduino-lmic

*Original reference of the edition of the libraries:

http://wiki.dragino.com/index.php?title=Use_the_LMIC_with_915MHZ_Dragino_Lora_boards


Comments
========

Test performed using NodeMCU-32S ESP32 connected to the Lora1276 (NiceRF).

NiceRF
======

http://www.nicerf.com/productslist_180.html

The 915 MHz ISM Band SHALL be divided into the following channel plans.
Upstream – 64 channels numbered 0 to 63 utilizing LoRa 125 kHz BW varying from
DR0 to DR3, using coding rate 4/5, starting at 902.3 MHz and incrementing linearly
by 200 kHz to 914.9 MHz
Upstream – 8 channels numbered 64 to 71 utilizing LoRa 500 kHz BW at DR4
starting at 903.0 MHz and incrementing linearly by 1.6 MHz to 914.2 MHz
Downstream – 8 channels numbered 0 to 7 utilizing LoRa 500 kHz BW at DR8 to
DR13, starting at 923.3 MHz and incrementing linearly by 600 kHz to 927.5 MHz
