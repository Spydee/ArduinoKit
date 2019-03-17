# Dave's Arduino Kit
Libraries and examples for ESP8266 Arduino with SH1106 display.
Supports the Si4703 radio and built in SH1106 OLED display using I2C
Supports Cirque Pinnacle sensor using SPI or I2C but SPI is the preferred protocol

There are two libraries in this repository.

## ArduinoKit library:
     Contains two sub-libraries, 
        one for the SH1106 display using I2C
        one for the Si4703 radio including RDS using I2C
        
## CirqueLib library:
     This library is for the Cirque Pinnacle based TM040040 and TM035035 track pads
     Contains code to read the data and scale it to a specific range
     Contains code with gestures to work with the sensor
            gestures are SWIPE UP, SWIPE DOWN, SWIPE LEFT, SWIPE RIGHT, TAP
            
            
Examples include a program that uses the touchpad to control the radio station and display the RDS data on the SH1106 display

