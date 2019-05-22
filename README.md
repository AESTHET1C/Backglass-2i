# Backglass 2 Pinball Controller Board

An Arduino Uno-compatible unified control board tailored to the Eli Whitney Museum 2019 summer pinball project.

The board contains the following hardware:

* Microchip ATmega8U2/16U2 (serial communication and code upload)
* Microchip ATmega328P (user code)
* Microchip ATmega48PB (audio/visual coprocessing)
* 4-character 7 segment display
* 2 analogue inputs (for reflectance sensors)
* 5 digital inputs (with integrated pull-ups)
* 3 current-limited LED outputs
* 1 PWM-controlled motor output
* 1 speaker output
* Micro USB interface
* 2.7 - 6.5 volt power input

All features of the board, with the exception of the motor, can be powered via USB.

-----

A user-oriented code library can be found here: <https://github.com/AESTHET1C/Backglass-2-Library/>

The coprocessor firmware can be found here: <https://github.com/AESTHET1C/Backglass-2-Firmware/>
