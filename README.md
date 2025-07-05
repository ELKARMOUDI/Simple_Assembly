# Cortex-M4 Assembly Register Increment Demo

## Description
Minimal ARM assembly program that:
1. Initializes registers `r5=0x64` and `r4=4`
2. Enters infinite loop, incrementing both registers by 1

## Key Features
- **Target**: ARM Cortex-M4
- **Instructions Used**:
  - `mov`: Register initialization
  - `add`: Increment operation
  - `B`: Branch (infinite loop)
- **No I/O**: Pure register manipulation example

## Usage
1. Assemble with ARM toolchain (e.g., `arm-none-eabi-as`)
2. Run on Cortex-M4 MCU or simulator
3. Observe registers increment in debugger

## Purpose
- Demonstrates basic Cortex-M4 assembly structure
