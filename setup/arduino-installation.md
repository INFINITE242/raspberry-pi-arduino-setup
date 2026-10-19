# Installing Arduino on Raspberry Pi OS Using Terminal

## 1. System Information

- Operating System: Debian GNU/Linux 13 (Trixie)
- Architecture: ARM64 (64-bit)
- Arduino IDE: 1.8.19
- Arduino CLI: 1.5.1

## 2. Update Raspberry Pi OS

Commands used:

```bash
sudo apt update
sudo apt upgrade -y
```

**Purpose:**
- `sudo apt update` refreshes the package lists.
- `sudo apt upgrade -y` installs available package updates.

## 3. Install Arduino IDE

Command used:

```bash
sudo apt install arduino -y
```

**Purpose:** Installs Arduino IDE from the system's package repositories.

To launch the IDE:

```bash
arduino
```

Installed version: 1.8.19

## 4. Install Arduino CLI

Arduino CLI allows us to manage board packages, libraries, compile sketches, and upload programs using Terminal.

Check the installed version:

```bash
arduino-cli version
```

Installed version: 1.5.1

## 5. Install ESP32 Board Support

Add the ESP32 package index:

```bash
arduino-cli config add board_manager.additional_urls https://espressif.github.io/arduino-esp32/package_esp32_index.json
```

Refresh package information:

```bash
arduino-cli core update-index
```

Install ESP32 support:

```bash
arduino-cli core install esp32:esp32
```

Installed version: 3.3.12

## 6. Install ESP8266 Board Support

Add the ESP8266 package index:

```bash
arduino-cli config add board_manager.additional_urls https://arduino.esp8266.com/stable/package_esp8266com_index.json
```

Refresh package information:

```bash
arduino-cli core update-index
```

Install ESP8266 support:

```bash
arduino-cli core install esp8266:esp8266
```

Installed version: 3.1.2

## 7. Verify Board Packages

Command:

```bash
arduino-cli core list
```

Expected installed packages:

- `esp32:esp32` — 3.3.12
- `esp8266:esp8266` — 3.1.2

## 8. Detect a Connected Board

Connect a board with a USB data cable and run:

```bash
arduino-cli board list
```

This checks whether Arduino CLI can detect the connected board and its port.

## 9. Install Arduino Libraries

Command used:

```bash
arduino-cli lib install "Adafruit SSD1306" "Adafruit GFX Library" "Adafruit BusIO" "Adafruit Unified Sensor" "DHT sensor library" "ArduinoJson" "PubSubClient" "OneWire" "DallasTemperature" "Adafruit MPU6050"
```

Verify the installed libraries:

```bash
arduino-cli lib list
```

Note: Verify the output of this command before marking the library installation as completed.

## Summary

Arduino IDE and Arduino CLI were installed on 64-bit Raspberry Pi OS. ESP32 and ESP8266 board support packages were installed and their versions verified.

Further work will include connecting hardware, compiling sketches, uploading programs, and documenting electronics experiments.
