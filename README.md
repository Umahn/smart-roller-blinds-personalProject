# Smart Roller Blinds

Automating manual crank-stick roller blinds using an Arduino Nano ESP32, 
a NEMA 17 stepper motor, and Home Assistant, with voice control via Google Home.

## Motivation
Wanted an introduction into embedded systems and wanted to make all blinds at home automated and connected via the same home assistant network 

## How It Works
- An Arduino Nano ESP32 drives a NEMA 17 stepper motor via an A4988 driver
- A 3D-printed/improvised coupler attaches the motor shaft to the blind's crank stick
- The motor turns the stick the same way a hand would, rolling the blind up or down
- [Once built out: ESPHome firmware connects the ESP32 to Home Assistant]
- [Once built out: Home Assistant exposes the device to Google Home for voice control]

## Hardware
- Arduino Nano ESP32
- NEMA 17 stepper motor
- A4988 stepper driver
- 12V power supply
- (Raspberry Pi running Home Assistant — planned)

## Status
🚧 In progress — currently working on: Connecting motor to power supply and testing rotation 
🟢 Completed - Basic software for motor rotations

## Progress Log
- 07/27/2026 — Setup Arduino IDE, confirmed ESP32 board communication with Blink test
- 08/02/2026 - Connected A4988 drive to Arduino on breadboard (Dir and Step Pins)
- 08/06/2026 — Completed motor rotation software and uploaded sketch onto Arduino. 
- ...

## What I Learned
- Learned how to connect board onto Arduino IDE and run a simple sketch
- 

## Next Steps
- [X] Wire and test bare motor
- [ ] Design/print coupler for crank stick
- [ ] Calibrate open/closed positions
- [ ] Set up Home Assistant on Raspberry Pi
- [ ] Integrate via ESPHome
- [ ] Connect to Google Home
