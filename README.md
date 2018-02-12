[![ MAG3110](MAG3110_I2C.png)](https://store.ncd.io/product/mag3110-3-axis-digital-magnetometer-electronic-compass-i2c-mini-module/).

#  MAG3110

The MAG3110 is a small, low-power, digital 3-axis magnetometer.This device can be used in conjunction with a 3-axis accelerometer to realize an orientation independent electronic compass that can provide accurate heading information.
This Device is available from www.ncd.io 

[SKU: MAG3110]

(https://store.ncd.io/product/mag3110-3-axis-digital-magnetometer-electronic-compass-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface MAG3110 3axis magnetometer With Raspberry Pi :
1. <a href="https://store.ncd.io/product/mag3110-3-axis-digital-magnetometer-electronic-compass-i2c-mini-module/">MAG3110 3Axis magnetometer sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python MAG3110.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
