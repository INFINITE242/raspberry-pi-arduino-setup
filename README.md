- [x] Verify Arduino libraries# Raspberry Pi Electronics

An ongoing record of setting up and using a Raspberry Pi for
electronics development, Arduino programming, microcontrollers,
circuits, and hardware experiments.

## Current environment

- Operating system: Debian GNU/Linux 13 (Trixie), 64-bit ARM
- Arduino IDE: 1.8.19
- Arduino CLI: 1.5.1
- ESP32 Arduino core: 3.3.12
- ESP8266 Arduino core: 3.1.2
- GitHub CLI: 2.46.0-3 (Debian package)

## Setup progress

- [x] Install Arduino IDE through apt
- [x] Install Arduino CLI
- [x] Install ESP32 board support
- [x] Install ESP8266 board support
- [x] Configure Git
- [x] Authenticate GitHub CLI
- [x] Verify Arduino libraries
- [x] Verify boards appear in Arduino IDE
- [ ] Connect and identify the physical microcontroller
- [ ] Upload and test the first sketch

## Documentation

- `setup/`: installation and configuration instructions
- `troubleshooting/`: errors, causes, and fixes
- `experiments/`: individual hardware projects and test results
- `circuits/`: circuit diagrams and wiring references
- `notes/`: additional observations and ideas

## Project principles

- Record commands and versions actually used.
- Keep a record of installation errors and their solutions.
- Include code, wiring, and measurements for experiments.
- Clearly distinguish planned, assembled, and tested projects.
- Never commit passwords, access tokens, or private credentials.

This repository is an ongoing work log. Hardware experiments
will be marked tested only after they have actually been tested.
### Arduino Installation Guide

See [Installing Arduino on Raspberry Pi OS Using Terminal](setup/arduino-installation.md).
- [Arduino installation guide](setup/arduino-installation.md)
- [Arduino libraries guide](setup/arduino-libraries.md)
### Setup Guides

- [Arduino installation](setup/arduino-installation.md)
- [Arduino libraries](setup/arduino-libraries.md)
- [ESP32 and ESP8266 setup](setup/esp-board-setup.md)
## Project Navigation

### Setup Guides
- [Arduino Installation on Raspberry Pi OS](setup/arduino-installation.md)
- [Arduino Libraries](setup/arduino-libraries.md)
- [ESP32 and ESP8266 Setup](setup/esp-board-setup.md)

### Electronics Experiments
- Individual experiments will be documented with instructions, code, wiring details, and photos.
- Each experiment will have its own folder for easy access.

### Circuits and Wiring
- Circuit diagrams, wiring references, and component connections.

### Troubleshooting
- Errors encountered during setup and experiments, with solutions.

## Experiment Documentation Standard

Every experiment should include, where applicable:

- **Objective:** What we want to test.
- **Components:** Parts used.
- **Wiring:** Pin connections and circuit diagram.
- **Code:** Complete, reusable source code.
- **Procedure:** Steps to reproduce the test.
- **Photos:** Actual setup, wiring, and working result.
- **Results:** What worked and what didn't.
- **Troubleshooting:** Errors and fixes.
- **Status:** Planned, assembled, or tested.
### Explore Experiments

Browse the [Electronics Experiment Index](experiments/README.md) for project ideas, instructions, code, wiring, and photos as projects are completed.
