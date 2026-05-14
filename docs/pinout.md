# GPIO / Pinout Planning

## Purpose

This document tracks planned GPIO usage and expansion planning for the P4 handheld project.

---

## Planned Interfaces

| Function | Notes |
|---|---|
| Main Display | Integrated display system |
| Navigation Buttons | Menu and interface control |
| Status LEDs | System indicators |
| I2C Bus | Sensors and OLED modules |
| SPI Bus | Future expansion hardware |
| USB Serial | Development and diagnostics |
| Wi-Fi | Telemetry and networking |
| Bluetooth | Portable connectivity |

---

## Reserved Expansion Areas

### Sensor Expansion

Planned support for:

- IMU modules
- Environmental sensors
- GPS modules
- Telemetry adapters

### Future Drone Interfaces

Possible future integrations:

- MAVLink telemetry
- Drone diagnostics
- Serial telemetry adapters
- CAN bus experimentation

---

## UI Hardware Concepts

### Input Devices

- Momentary push buttons
- Directional navigation
- Rotary encoder experimentation

### Display Concepts

- Primary display dashboard
- Secondary status displays
- Minimal aviation-inspired layouts

---

## Development Strategy

Current goal:

Keep GPIO assignments flexible during early prototype stages until enclosure layout and UI architecture stabilize.
