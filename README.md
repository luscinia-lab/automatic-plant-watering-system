# Automatic Plant Watering

## Overview

This project is an automatic plant watering system developed using ESP32.

The system monitors soil moisture and sunlight conditions, then supplies water through hoses to plants installed throughout the house.

## Purpose

I developed this system to reduce the effort required for plant care and create an environment where multiple plants can be managed automatically.

## Features

### Automatic Watering

- Measures soil moisture using sensors.
- Automatically supplies water when soil moisture falls below a set threshold.
- Considers sunlight conditions and selects an appropriate watering timing.
- Avoids watering during strong sunlight conditions.
- Distributes water through hoses to multiple plants.

### Manual Control

- Allows manual adjustment of watering.
- Users can control the system depending on plant conditions.

### Home Installation

- Installed in a three-story house.
- Designed to manage watering for plants located throughout the house.

## Hardware

- ESP32
- Soil moisture sensors
- Light sensor
- Water pump
- Relay module
- Water hoses
- Electronic components

## Software

- Arduino IDE
- C/C++

## Development

The ESP32 collects information from soil moisture sensors and sunlight sensors.

Based on environmental conditions, the system determines the appropriate timing for watering and controls the water pump.

Water is distributed to multiple plants through hoses connected to the pump.

## Result

(Add photos and videos of the installed system here)

## Future Improvements

- Add wireless monitoring
- Improve water distribution accuracy
- Reduce power consumption
- Create a more compact design
- Create a more compact design
