# ESP32 and ESP8266 Board Setup

## Environment
- OS: Debian GNU/Linux 13 (Trixie), ARM64
- Tool: Arduino CLI

## ESP32

Package index:
https://espressif.github.io/arduino-esp32/package_esp32_index.json

Add the package index:

```bash
arduino-cli config add board_manager.additional_urls https://espressif.github.io/arduino-esp32/package_esp32_index.json
