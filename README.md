# STM32-Based-DC-Motor-Control-System-using-PWM
STM32-based DC motor speed control using PWM with push buttons for ON/OFF, speed increase, and speed decrease.
# STM32 DC Motor Control using PWM

## Overview

This project demonstrates DC motor speed control using PWM (Pulse Width Modulation) with STM32F103C8T6 (Blue Pill). The system uses three push buttons to control motor ON/OFF and adjust speed.

---

## Features

* Motor ON/OFF using push button
* Speed increase using button
* Speed decrease using button
* PWM-based efficient motor control

---

## Working

* Button 1 → Toggle motor ON/OFF
* Button 2 → Increase speed (increase duty cycle +5%)
* Button 3 → Decrease speed (decrease duty cycle -5%)

---

## Hardware Used

* STM32F103C8T6 (Blue Pill)
* DC Motor
* Motor Driver (L298N)
* 3 Push Buttons

---

## Pin Configuration

| Component      | STM32 Pin |
| -------------- | --------- |
| PWM Output     | PA1       |
| ON/OFF Button  | PB0       |
| Speed Increase | PB1       |
| Speed Decrease | PB10      |

---

## Software Used

* STM32CubeMX
* Keil uVision
* Embedded C

---

## Demo

(Add your project images here
## 🎥 Demo Video

[Watch Motor Running Video](https://drive.google.com/file/d/1DBJ4HqE5uqFQ9R1SAauPwjifIZeeNPna/view?usp=sharing)

---

## 🚀 Future Improvements

* Add LCD display
* Add Bluetooth (ESP32) control
* Implement PID control

---

## Author

Saqib Ishaq – Electrical Engineering Student (PIEAS)
