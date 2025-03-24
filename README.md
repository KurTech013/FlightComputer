# FlightComputer
This will contain all progress and resources for MSOEs HPRC custom flight computer

--------------------
Flight Computer v1
--------------------
Microcontroller:
1. easy = esp32 based
2. hard but way better = stm32 stm32f405

Features:
1. run off two small lipo batteries (for redundancy)
2. live telemetry using E32 LoRa module by EBYTE (custom data transmistion?)
3. place to attach switch
4. voltage and current monitoring
5. writting to sd card
6. Indication LEDS
7. Indication with buzzer
8. tilt-lock
9. Apogee detection using accelemeter and barometer
10. 6 pyro channels for staging / parachute deplyment
11. event timing?

Components/Chips:
1. Barometer/Altimeter -> MS5611,BMP388
2.  IMU(Accelerometer + Gyro) MPU6050, MPU9250
3. SD card
4. possible flash storage
5. IRLZ44N or PMPB10NX (or similar) -> for events like staging or parchute deployment, with fuses/ high side switch?
6. current and voltage sense chip -> INA260
7. 5v regulator

Stretch Goals:
1. servo control
2. camera control
3. seperate battery for pyro channels

Helpful videos:
1. https://www.youtube.com/watch?v=nUywu65qgFY&t=634s

