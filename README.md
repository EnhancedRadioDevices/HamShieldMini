
HamShieldMini1.1 Hardware


These are the hardware design files for the HamShieldMini1.1 electronics.

These hardware files were created with KiCAD. 
You may need the KiCAD libraries available here: https://github.com/mogar/KiCAD_libs
When opening these projects in KiCAD, you may need to change the path to the libraries from the above link.
This can be done in preferences->libraries in both the schematic editor and the layout editor.
Make sure the libraries noted there point to wherever you put the above KiCAD_libs repo.

# Arduino Connections

To use the HamShieldMini with an Arduino, you can use our standard HamShield library: 

https://github.com/EnhancedRadioDevices/HamShield

The pinout should be:

    1	- SPKR - Arduino Pin A2
    2	- MIC  - Arduino Pin D3
    3	- CLK  - Arduino Pin A6
    4	- nCS  - Arduino Pin A1
    5	- DAT  - Arduino Pin A4
    6	- GND  - Arduino Pin GND
    7	- VCC  - Arduino Pin 5V

# Raspberry Pi Connections

To use the HamShieldMini with a Raspberry Pi, you can use our HamShieldPy library: 

https://github.com/EnhancedRadioDevices/HamShieldPy

The pinout should be:

    2	- MIC  - RPi Pin 12 (wiringPi1, PWM0)
    3	- CLK  - RPi Pin 15 (wiringPi3)
    4	- nCS  - RPi Pin 11 (wiringPi0)
    5	- DAT  - RPi Pin 13 (wiringPi2)
    6	- GND  - RPi Pin 1 (3.3V)
    7	- VCC  - RPi Pin 6 (GND)
