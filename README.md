# SMORRT
Smart Management of Rocket Recovery and Telemetry

Avionics PCB for High-Power Rocketry

Embedded Software for this board available here: https://github.com/lucaspallez/SMORRT_Software
Compatible Ground Station PCB: https://github.com/lucaspallez/GRUND

## Features
- Computation: Teensy 4.1
- Telemetry: RFM95W LoRa Module (with SMA connector)
- IMU: MPU 6050 Breakout
- Barometer: BMP 280 Breakout
- GPS: Ublox NEO-M8J Module (with SMA connector)
- Data logging: 1Mbit FRAM IC + Teensy SD Card slot with locking screw
- Power Output: 4 MOSFET Pyro outputs with E-match detection, 2 Servo compatible (via PWM)
- Battery Management: 2x 1s Li-Ion Battery chargers
- Power Inputs: 2x Redundant 1s Li-Ion Battery connectors + 1x 12V Battery connector for power
- Arming: 1x Main external arm switch + 1x Power out external arm switch
- Status Indicators: 5x User programmable LEDs, 1x Buzzer
- Battery voltage readings

## Changes planned:
- Reduce the physical size to fit in smaller diameter rockets

## Documentation

Designed with KiCAD 5.5

TODO
