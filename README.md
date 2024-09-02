# ESP32_BMM150
 
Add the following libraries:

https://github.com/mjs513/Modified-BMI160---BMM150-Arduino-Libraries

The only thing you need to change is:

Wire.setPins(16, 17);//(SDA,SCL) 

Since I have ESP32-S3 in my hand and iomux features, So connect the dots.

SDA -> Pin 16

SCL -> Pin 17

if you have ESP32 in hand and do not have iomux, You need to add Wire.setPins(16, 17); (SDA, SCL) remove, after which connect the wire to the default RX, TX pins.
