# PicoW_DS1307
Code for running the DS1307 RTC on a PicoW using the C SDK

# Current Features
# Reading the DS1307
* Read the Clock output in 12 Hour Mode in the layout HH:MM:SS AM/PM or HH:MM AM/PM
* Read the clock output in 24 Hour Mode in the layout HH:MM:SS or HH:MM
* Read the current day (Sunday - Saturday)
* Read the current date in the format XX (ex. 05)
* Read the current month in the format MM or MNTH (ex. 05 or May)
* Read the current year in the format 20XX (ex. 2025)

# Setting the DS1307
* Set the clock in either 12/24 Hour Mode in hours and minutes, seconds is set to 0.
* Set the current day (1 - 7)
* Set the current date (1 - 31)
* Set the current month (1 - 12)
* Set the current year (0 - 99)

# Notice:
The SSD1306 code is used for debugging purposes and is not required to run the DS1307 code.

# Base Code For The SSD1306: 
https://github.com/raspberrypi/pico-examples/blob/master/i2c/lcd_1602_i2c/lcd_1602_i2c.c
