# FlightComputer
This will contain all progress and resources for MSOEs HPRC custom flight computer

--------------------
Flight Computer v1
--------------------
Microcontroller:
easy = esp32 based
hard but way better = stm32 stm32f405

Features:
1. run off two small lipo batteries (for redundancy)
2. live telemetry using E32 LoRa module by EBYTE (custom data transmistion?)
3. place to attach switch
4. voltage and current monitoring
5. writting to sd card

Components/Chips:
1. Barometer/Altimeter -> MS5611,BMP388
2.  IMU(Accelerometer + Gyro) MPU6050, MPU9250
3. SD card
4. possible flash storage
5. IRLZ44N or PMPB10NX (or similar) -> for events like staging or parchute deployment, with fuses/ high side switch?
6. current and voltage sense chip -> INA260
7. 5v regulator

Helpful videos:
1. https://www.youtube.com/watch?v=nUywu65qgFY&t=634s

