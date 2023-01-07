# bme280-python

Python 3 script to read data from a BME280 sensor.

Tested with the [Waveshare BME280](https://www.waveshare.com/wiki/BME280_Environmental_Sensor) environmental sensor.

Based on Python 2 code from [Matt Hawkins](https://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/)

## Requirements

* This script does not work on Windows.
* Update the I2C address (use `i2cdetect -y 1`, it should be `76` or `77`)
* Update the bus passed to `SMBus()` based on your Pi version
* Install the Python package: [smbus2](https://pypi.org/project/smbus2/)

## Alternative

Python 3 package **[bme280-python](https://github.com/pimoroni/bme280-python)** provided by [Pimoroni](https://shop.pimoroni.com/).