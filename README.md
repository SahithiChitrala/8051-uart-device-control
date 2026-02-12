# 8051 UART Based Device Control

## 📌 Project Overview

This project demonstrates UART-based serial communication using the 8051 microcontroller to control external devices through GPIO pins.

Commands received over UART are used to control two output devices (Lamp and Fan). The system also provides status feedback via serial communication.

---

## 🎯 Objective

To implement bidirectional UART communication and apply it to real-time device control using Embedded C.

---

## 🔧 Features

- UART initialization using Timer1 (Mode 2)
- 9600 baud serial communication
- GPIO control using `sbit`
- Command-based device switching
- Serial feedback to user
- Continuous polling-based operation

---

## 🛠 Hardware Used

- 8051 Microcontroller
- Serial communication interface (UART)
- LEDs (used to simulate Lamp & Fan)
- Keil uVision IDE

---

## 🧠 Concepts Applied

- UART configuration (SCON, TMOD, TH1)
- Serial buffer handling (SBUF)
- Polling method using TI and RI flags
- Bit-addressable port control
- Switch-case command handling logic

## 🗂 Repository Structure

  
---

## 📈 Future Improvements

- Add interrupt-based UART
- Add command validation
- Add LCD feedback
- Convert to reusable UART driver module


---




