## [1.5.2] - 2016-04-29

### Changes

- Add Example, MoveTest, GetXYZ, Recording Mode


## [1.5.2] - 2016-04-29

### Changes

- Cancel v.1.5.0 read offset from EEPROM.


## [1.5.0] - 2016-04-14

### Changes

- Initialize servo offset & linear offset from EEPROM to global values, prevent read EEPROM every time

- Use [EEPROM.get()][a4e46a5d] & [EEPROM.put()][275bf48d] to read & write value in EEPROM instead of saveDataToRom()

  [a4e46a5d]: https://www.arduino.cc/en/Reference/EEPROMGet "EEPROM.get()"
  [275bf48d]: https://www.arduino.cc/en/Reference/EEPROMPut "EEPROM.put()"

- rename function readToAngle to analogToAngle
- Change Offset address in EEPROM

## [1.4.0] - 2016-04-12

### Changes

- uarm_library.cpp writeServoAngle resume LEFT & RIGHT ANGLE

- ToDo: remove LEFT & RIGHT ANGLE from WriteServoAngle (For Safety)


## [1.3.1] - 2016-04-12

### Changes

- uarm_library.cpp writeLeftRightServoAngle() Update the angle between left & right  

- Change Folder examples folder & stretch name From UarmFirmata to UArmFirmata  