# Adafruit PCA9685 servo controller to control a L298N H-Bridge
With this two Python programs and the Adafruit PCA9685 Python library it is possible to use a PCA9685 servo controller to control a L298N H-Bridge. Due to the fact that the Raspberry Pi has problems to generate a clear PWM signal I am using the PCA9685 servo controller to generate the PWM signal for the L298N H-Bridge to set the spinning speed.

The PCA9685 servo controller board is connected via the I2C bus to a Raspberry Pi.

The picture below shows my setup:

![PCA9685 servo controller with a L298N H-Bridge setup](https://custom-build-robots.com/wp-content/uploads/2017/05/L298N_H-Bridge_PCA9685_02-300x225.jpg)
