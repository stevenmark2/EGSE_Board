# EGSE Board

**Ground Support Electronics for CubeSat Pre-Flight Testing**
*Texas Spacecraft Laboratory · UT Austin*

> ⚠️ Design files (schematics, layout, gerbers) are proprietary to Texas Spacecraft Laboratory and are not publicly available.

---

## Overview

The EGSE (Electrical Ground Support Equipment) board is a custom-designed PCB used for pre-flight testing and verification of the CubeSat's Command and Data Handling (CDH) subsystem. It provides a controlled interface between the flight hardware and the testing infrastructure used by the TSL team before integration.

## What It Does

- Provides a USB-C interface for communicating with flight hardware from a ground station laptop
- Monitors system voltages and currents during pre-flight checkout
- Routes CDH subsystem signals to test-accessible connectors for verification and debugging
- Acts as a bridge between flight-standard connectors (Micro-D) and standard lab test equipment

## Key Design Features

- **MCU:** Texas Instruments MSPM0 microcontroller handling USB-C communication and system monitoring
- **Interface:** USB-C connector for ground station connection
- **Signal routing:** Flight-standard connector pinouts accessible for test equipment
- **Power monitoring:** Voltage and current sensing on key rails
- **Form factor:** Designed to mate with the CubeSat stack during ground testing without being installed on the flight unit

## Role

Designed schematic, PCB layout, and firmware for this board as part of the Electrical Power Systems team at Texas Spacecraft Laboratory. Board was used in pre-flight verification procedures for the CDH subsystem.

## Related

- [Flight Prep Panel](../flight-prep-panel) — passive signal routing board that pairs with this EGSE board

---

*Part of ongoing CubeSat mission work at Texas Spacecraft Laboratory, UT Austin.*
