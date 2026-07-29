# Smart Botanical Garden

An IoT-enabled rooftop garden system designed to monitor environmental conditions and automate cooling and irrigation.

The project combined environmental sensors, solar power, mist-based cooling, and automated control logic to create more suitable growing conditions on a hot rooftop.

## Overview

Rooftop gardens are exposed to high temperatures, direct sunlight, and rapidly changing environmental conditions.

These conditions can:

- Increase plant stress
- Reduce soil moisture
- Raise irrigation requirements
- Make manual monitoring difficult
- Limit plant growth during hot weather

The Smart Botanical Garden was designed to monitor these conditions and respond automatically.

## The Problem

Traditional rooftop gardens generally depend on manual observation and watering.

This creates several challenges:

- Temperature changes may not be detected quickly
- Watering may be inconsistent
- Plants may be exposed to excessive heat
- Environmental data is not recorded
- Cooling systems may run unnecessarily
- Manual intervention is required frequently

The goal was to create a low-cost system that could sense environmental conditions and automatically control the garden environment.

## Solution

The system used sensors to monitor:

- Temperature
- Humidity
- Light intensity

The sensor data was used to trigger mist cooling and irrigation based on predefined environmental conditions.

The system also incorporated rooftop solar power to reduce dependence on grid electricity.

## Key Components

- Temperature sensor
- Humidity sensor
- Light sensor
- Microcontroller
- Water pump
- Mist nozzles
- Solar panel
- Control relay
- Water reservoir
- Automated control logic

## How It Works

1. Sensors continuously measure temperature, humidity, and light.
2. The controller compares readings with predefined thresholds.
3. When temperature rises or humidity falls beyond the target range, the misting system activates.
4. Fine mist cools the rooftop environment and increases local humidity.
5. The system stops automatically once conditions return to the desired range.
6. Solar power supports the operation of the sensing and cooling system.

## System Architecture

```text
Environmental Sensors
        |
        v
   Microcontroller
        |
        v
 Decision Logic
   /         \
  v           v
Misting     Irrigation
System       System
        |
        v
Improved Garden Conditions
