# Backglass 2 Integrated Pinball Controller Board

This is the "integrated" version of the [Backglass 2 Pinball Controller Board](https://github.com/AESTHET1C/Backglass-2). The I/O has been changed from wire receptacles to a ribbon cable, and the ordering has changed to better suit wire management.

---

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
