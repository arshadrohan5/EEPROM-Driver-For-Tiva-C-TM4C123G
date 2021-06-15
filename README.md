# EEPROM-Driver-For-Tiva-C-TM4C123G
Driver for using the on-board EEPROM of Tiva C TM4C123G
Add the files in your project and use the functions declared in the header file.
To write to EEPROM you need to provide block number (0 - 31) and address (0 - 15) along with data.
To read from EEPROM you need to provide block number (0 - 31) and address (0 - 15). Data stored at the location is then returned.
