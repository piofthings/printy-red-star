Backup Binaries on Octopi
Source: https://forum.arduino.cc/index.php?topic=403201.0

**Backup**

`avrdude -p atmega2560  -c stk500v2 -P COM10 -b 115200 -U flash:r:flash_backup_file.hex`

`avrdude -p atmega2560  -c stk500v2 -P COM10 -b 115200 -U eeprom:r:eeprom_backup_file.hex`


LmyStar COM Port
`avrdude -c stk500v2 -p atmega2560 -P /dev/ttyUSB0 -b 115200 -U flash:r:flash_backup_file.hex`

`avrdude -p atmega2560 -c stk500v2 -P /dev/ttyUSB0 -b 115200 -U eeprom:r:eeprom_backup_file.hex`


**Restore Binaries**
`avrdude -p atmega2560 -c stk500v2 -P COM10 -b 115200 -e -U flash:w:flash_backup_file.hex`

`avrdude -p atmega2560 -c stk500v2 -P COM10 -b 115200 -U eeprom:w:eeprom_backup_file.hex`

LmyStar COM Port
`avrdude -p atmega2560 -c stk500v2 -P /dev/ttyUSB0 -b 115200 -e -U flash:w:flash_backup_file.hex`

`avrdude -p atmega2560 -c stk500v2 -P /dev/ttyUSB0 -b 115200 -U eeprom:w:eeprom_backup_file.hex`
