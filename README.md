# 8051 UART Based Home Automation

## 📌 Project Overview

This project implements a basic home automation system using the 8051 microcontroller.  
Devices such as a Lamp and Fan are controlled through serial commands received via UART.

The system listens for user commands and switches devices ON or OFF accordingly, while sending status feedback through serial communication.

---

## 🎯 Objective

To design and implement a simple command-based home automation system using:

- UART communication
- GPIO control
- Embedded C programming

---

## ⚙️ Working Principle

1. UART is initialized using Timer1 in Mode 2 (9600 baud).
2. The system continuously waits for a character from the serial terminal.
3. Based on the received command:

   | Command | Action |
   |----------|--------|
   | '1' | Lamp ON |
   | '2' | Lamp OFF |
   | '3' | Fan ON |
   | '4' | Fan OFF |

4. The system sends a confirmation message back through UART.

---

## 🔧 Hardware Used

- 8051 Microcontroller
- 11.0592 MHz Crystal Oscillator
- LEDs (used to simulate Lamp & Fan)
- UART Serial Interface
- Keil uVision IDE

---

## 🧠 Concepts Applied

- UART initialization using SCON, TMOD, TH1
- Polling-based serial communication (TI & RI flags)
- Bit-addressable GPIO using `sbit`
- Command parsing logic
- Embedded firmware structure

---

## 📂 Repository Structure

