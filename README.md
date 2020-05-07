# Gesture-Recognition
Sign language recognition using flex sensors, gyroscope, accelerometer and raspberry pi mounted on glove.

Hardware Used: Raspberry Pi Model 4B, MPU6050, PCF8591, Flex sensors (5)

Raspberry Pi,unlike Arduino, does not have any analog input pins, hence we need to use an A/D Converter (PCF8591) to obtain 8 bit digital
values from the analog flex sensors.
