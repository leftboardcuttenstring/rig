# rig

## Description
Firmware for a password storage device based on STM32F401CC / STM32F411CC microcontrollers.  
Written in C.

## Target Hardware
- MCU: STM32F401CC / STM32F411CC
- Architecture: ARM Cortex-M4

## Functionality
- Secure storage of passwords
- Access to stored data via device interface

## Project Structure
- `app/` — source files
- `config/` — project config
- `platform/` — startup-files, linker scripts etc.

## Requirements
- ARM GCC Toolchain
- STM32 HAL / CMSIS
- Make