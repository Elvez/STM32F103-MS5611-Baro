# STM32F103-MS5611-Baro
Firmware for STM32F103C8T6 to get pressure and temperature readings via I2C. I have used CubeMx to generate init code and used
no library for the sensor. There are comments given for changing configuration of the sensor. 
Just connect the sensor to the I2C1 peripheral of the bluepill and connect Serial Wire debugger, or you can use serial to flash
firmware.
