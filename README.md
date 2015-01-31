# SilviaPID
PID controller for Rancilio Silvia espresso machine (Arduino)

This software is leveraged from Nicolas Kruchten's work (https://github.com/nicolaskruchten/silvia) and the TC4
libraries (http://code.google.com/p/tc4-shield/).

My contributions include:
 * Class hierarchy for Thermocouples used, i.e. a base Thermocouple class with derived classes for Type J and
   Type K thermocouples.
 * Command processor to configure the applications with the EEPROM in the TC4.
 * Replaced the WiFi interface with a 20x4 I2C LCD for the display device.

Note that this code is not running with a real espresso machine yet!  I am currently finishing a Mahogany case for
the circuitry and then we'll install it!  (And the case is round since I have a lathe but not a table saw!)

I will post the code to date in the next day or two.
