# STM32 WS2812B Addressable LED Project

A small project created to explore STM32 development and gain a deeper understanding of the WS2812B addressable LED protocol.

## Overview

This project provides a straigntforward interface for controlling WS2812B Adressable LEDs.

## Features

- Complete RGB control of each addressable led
- Using integrated ADC to control led brightness

## Hardware

- STM32 development board: Blackpill (STM32411CEU6)
- WS2812B addressable LED (in a PC case fan)

## Software and Tools

- STM32CubeIDE
- STM32CubeMX
- HAL (provided by CubeIDE)
- Programming/debugging tool: ST-Link v2

# Getting started
## Requirements
- Stm32CubeIDE
- Debugger (ST-Link / J-Link)
- STM32 Developement board

# Building
1. Clone the repository
```bash
git clone https://github.com/Tombays/stm32-WS2812B-led-control-through-dma
cd stm32-WS2812B-led-control-through-dma
```
2. Open the project in STM32CubeIDE.
3. Configure the project if necessary.
4. Build the project.

## Configuration
Project provides next configuration options in `main.c`:

- `NUM_LEDS <NUMBER of leds in a strip>`
- `WS2812_RESET_BITS <How many 1.25us bits to send to latch/reset the leds>`

# Usage
## How It Works

For a detailed explanation of the project, see:

[HOWITWORKS.md](/HOWITWORKS.md)
