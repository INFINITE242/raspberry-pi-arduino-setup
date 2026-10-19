# Arduino Libraries

These libraries were installed using Arduino CLI on Raspberry Pi OS.

## Installed Libraries

| Library | Installed Version | Purpose |
|---|---|---|
| Adafruit BusIO | 1.17.4 | Communication support for Adafruit libraries |
| Adafruit GFX Library | 1.12.6 | Graphics drawing for displays |
| Adafruit MPU6050 | 2.2.9 | Interface with MPU6050 motion sensor |
| Adafruit SSD1306 | 2.5.17 | Control SSD1306 OLED displays |
| Adafruit Unified Sensor | 1.1.15 | Common sensor interface |
| ArduinoJson | 7.4.3 | Parse and generate JSON data |
| DallasTemperature | 4.0.6 | Read Dallas/Maxim temperature sensors |
| DHT sensor library | 1.4.7 | Read DHT temperature and humidity sensors |
| OneWire | 2.3.8 | Communicate with OneWire devices |
| PubSubClient | 2.8 | MQTT messaging for IoT projects |

## Installation Command

```bash
arduino-cli lib install "Adafruit SSD1306" "Adafruit GFX Library" "Adafruit BusIO" "Adafruit Unified Sensor" "DHT sensor library" "ArduinoJson" "PubSubClient" "OneWire" "DallasTemperature" "Adafruit MPU6050"
