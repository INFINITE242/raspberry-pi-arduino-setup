# ESP32-C3 OLED Test

## Test 1: OLED Working Message
Displays "ESP32-C3 Test" and "OLED Working!"

## Test 2: Name Display
Displays a greeting and my name.

## Wiring
- OLED GND → ESP32-C3 GND
- OLED VDD → ESP32-C3 3V3
- OLED SCK/SCL → GPIO 9
- OLED SDA → GPIO 8

## Arduino IDE
- Upload speed: 115200
- I2C address: 0x3C
- Display resolution: 128 × 64

## Photos
Photos of the wiring and both tests will be stored in the `photos/` folder.
