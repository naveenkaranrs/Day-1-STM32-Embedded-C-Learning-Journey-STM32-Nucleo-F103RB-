# 🚀 STM32 Embedded C Learning Journey - Day 1

Welcome to my **STM32 Embedded C Learning Journey**! This repository documents my daily progress while learning **Embedded C** using the **STM32 Nucleo-F103RB** development board. My goal is to build a strong foundation in embedded systems by understanding the hardware, ARM Cortex-M architecture, and register-level programming before moving to advanced embedded concepts.

---

## 📅 Day 1 - Introduction to STM32 Nucleo-F103RB

**Date:** July 6, 2026

### 🎯 Learning Objectives

- Understand the STM32 microcontroller family.
- Explore the STM32 Nucleo-F103RB development board.
- Learn the difference between a Datasheet, Reference Manual, and User Manual.
- Identify the major hardware components on the board.
- Understand the purpose of ST-LINK.
- Learn basic embedded system terminology.

---

## 📚 Topics Covered

### 1. What is STM32?

STM32 is a family of 32-bit ARM Cortex-M microcontrollers developed by STMicroelectronics. These microcontrollers are widely used in embedded systems because of their high performance, low power consumption, and rich set of peripherals.

### 2. STM32 Nucleo-F103RB Overview

The STM32 Nucleo-F103RB board is built around the STM32F103RB microcontroller and is ideal for learning embedded systems.

**Specifications**

- Microcontroller: STM32F103RB
- CPU: ARM Cortex-M3
- Maximum Clock Speed: 72 MHz
- Flash Memory: 128 KB
- SRAM: 20 KB
- Operating Voltage: 3.3V
- On-board ST-LINK/V2-1 Debugger/Programmer
- User LED (LD2)
- User Push Button (B1)
- Arduino Uno R3 Compatible Headers
- Morpho Expansion Headers

---

## 📖 Documents Studied

### 📄 Datasheet

The datasheet provides the electrical and hardware specifications of the microcontroller.

It includes:
- Pin descriptions
- Memory information
- Electrical characteristics
- Alternate pin functions
- Package information
- Operating voltage

---

### 📘 Reference Manual

The reference manual explains how each peripheral works internally.

Topics include:
- GPIO
- RCC
- UART
- SPI
- I2C
- Timers
- ADC
- Interrupts
- DMA

---

### 📗 User Manual

The user manual describes the development board itself.

It explains:
- Board layout
- LED connections
- Push buttons
- Power supply
- ST-LINK debugger
- Pin mapping
- Connectors

---

## 🔧 Board Components Learned

- STM32F103RB Microcontroller
- ST-LINK Programmer/Debugger
- USB Connector
- User LED (LD2)
- User Push Button (B1)
- Reset Button
- Arduino Headers
- Morpho Headers
- Power LEDs

---

## 🧠 Important Concepts

### Microcontroller (MCU)

A microcontroller is a complete computer on a single chip containing:

- CPU
- Flash Memory
- SRAM
- GPIO
- Timers
- UART
- SPI
- I2C
- ADC

---

### ARM Cortex-M3

The ARM Cortex-M3 is the processor core inside the STM32F103RB responsible for executing Embedded C programs.

---

### Flash Memory

- Stores the application program.
- Non-volatile memory.
- Data remains after power is turned off.

---

### SRAM

- Stores variables during program execution.
- Volatile memory.
- Data is lost when power is removed.

---

### GPIO (General Purpose Input Output)

GPIO pins can be configured as:

- Digital Input
- Digital Output
- Alternate Function
- Analog Input

GPIO allows the microcontroller to communicate with external devices such as LEDs, buttons, sensors, and displays.

---

## 🔌 What is ST-LINK?

ST-LINK is the on-board programmer and debugger.

It is used to:

- Upload Embedded C programs
- Debug applications
- Set breakpoints
- Monitor variables
- Access memory and registers
- Provide Virtual COM Port communication

---

## 📂 Documents to Explore Next

- STM32F103RB Datasheet
- STM32F103 Reference Manual
- STM32 Nucleo-F103RB User Manual

---
