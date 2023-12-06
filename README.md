# i2c_old
Sample code for slave I2C on a PIC18F46K42 using MCC core 4.65 libraries

MCC core 4.65 generates a sample application emulating a serial EEPROM.
MCC core 4.85.0 generates a more skeletal driver that requires functionality to be added through callbacks

The pin assignments allow for connecting a PICkit serial analyser to the 6 pin programming connector and using I2C over RB6 and RB7
