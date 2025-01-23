# Automated Sugarcane Vending Machine - Arduino Project

Welcome to the **Automated Sugarcane Vending Machine** project! This repository documents our journey in embedded systems programming using **Arduino**, as we prepare for the design and development of an automated vending machine.

## Project Overview

The goal of this project is to build an **automated sugarcane vending machine** with functionalities such as:
- Indicating juice pouring and dispensing using LEDs.
- Custom juice combination selection.
- Automating the entire juice preparation and dispensing process.

### Current Focus
We are currently practicing the basics of Arduino programming and hardware interaction, laying the groundwork for the main project.

---

## Current Progress

### Basic AVR Programming Practice
- **LED and Button Control**:
  - Using Arduino to configure GPIO pins for LED and button interaction.
  - Implementing basic input/output logic.
- **Multi-LED Control**:
  - Extended the practice to control multiple LEDs and buttons.

### LED Logic for Juice Dispensing
- Simulated juice pouring and dispensing using LEDs:
  - LEDs light up to indicate the progress of juice pouring.
  - Multiple LEDs represent juice combination selection.
  - Visual feedback for completion or error states.

---

## Repository Structure

```plaintext
├── Code/
│   ├── led_button_practice.ino       # Arduino code for basic LED and button logic
│   ├── juice_dispensing_led_logic.ino # Simulated LED logic for juice dispensing
├── Diagrams/
│   └── circuit_diagram.png           # Circuit diagram for practice setup
├── README.md                         # This file

## How to Run





Requirements

Hardware:
Arduino Board (e.g., Uno, Mega)
LEDs, resistors, buttons, and wires

Software:
Arduino IDE for writing and uploading code

Steps

Clone this repository: git clone https://github.com/your-username/sugarcane-vending-machine.git

Open the .ino files in the Arduino IDE.

Connect your Arduino board to your computer.

Upload the code to your Arduino board.

Connect the circuit as per the circuit_diagram.png and observe the LED functionality.
