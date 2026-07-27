# Smart Roller Blinds

Automating manual crank-stick roller blinds using an Arduino Nano ESP32, 
a NEMA 17 stepper motor, and Home Assistant, with voice control via Google Home.

## Motivation
[Why you started this — e.g. tired of manually cranking blinds, wanted to learn embedded systems]

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
🚧 In progress — currently working on: [fill in as you go, e.g. "getting the bare motor spinning via Arduino IDE"]

## Progress Log
- [Date] — Set up Arduino IDE, confirmed ESP32 board communication with Blink test
- [Date] — Motor/driver ordered
- ...

## What I Learned
[Fill in as you go — e.g. how stepper motors work, what a motor driver does, wiring/grounding basics]

## Next Steps
- [ ] Wire and test bare motor
- [ ] Design/print coupler for crank stick
- [ ] Calibrate open/closed positions
- [ ] Set up Home Assistant on Raspberry Pi
- [ ] Integrate via ESPHome
- [ ] Connect to Google Home