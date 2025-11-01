# ENAE100 Schematics



Logs IMU + barometer data on a Teensy 4.1



## Hardware

- Teensy 4.1 (onboard microSD)

- Adafruit LSM9DS1 (IMU)

- Adafruit BMP388 (barometer)



**I²C pins on Teensy 4.1:**

- SDA → pin 18 (A4)

- SCL → pin 19 (A5)

- Power sensors from \*\*3.3 V\*\*, and connect \*\*GND\*\*.  



## Wiring

Teensy 4.1 ↔ LSM9DS1 ↔ BMP388  

- 3.3V → VIN  

- GND → GND  

- 18/A4 (SDA) → SDA  

- 19/A5 (SCL) → SCL





