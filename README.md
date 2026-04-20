# 🔥 Microwave Oven using PIC16F877A

This project is a microcontroller based simulation of a microwave oven built using PIC16F877A. It demonstrates real time embedded system design with multiple cooking modes and user interaction.

---

## 📌 Features

- 🍲 Multiple Cooking Modes:
  - Micro
  - Grill
  - Convection

- ⏱️ Time Control:
  - Set cooking time in MM:SS format
  - Real time countdown using timer interrupt

- 🌡️ Temperature Control:
  - Temperature input for convection mode
  - Preheating functionality

- ⌨️ User Input:
  - 4x3 Matrix Keypad for input

- 📟 Display:
  - 16x4 CLCD interface (4-bit mode)

- ⚙️ Controls:
  - Start, Pause, Resume, Stop

- 🔔 Alerts:
  - Buzzer indication on completion and invalid inputs

---

## 🛠️ Technologies Used

- Embedded C
- PIC16F877A Microcontroller
- MPLAB X IDE
- XC8 Compiler
- Matrix Keypad
- CLCD (16x2)
- Timers & Interrupts

---

## 📂 Project Structure
├── main.c

├── main.h

├── clcd.c

├── clcd.h

├── matrix_keypad.c

├── matrix_keypad.h

├── timers.c

├── timers.h

├── isr.c


---

## ⚙️ How It Works

- System starts with a welcome screen on CLCD
- User selects cooking mode using keypad
- Time (and temperature for convection) is set
- Timer interrupt handles countdown
- Fan and buzzer are controlled based on system state

---

## ▶️ How to Run

1. Open project in MPLAB X IDE  
2. Select PIC16F877A device  
3. Build using XC8 compiler  
4. Flash the code to the microcontroller  
5. Connect:
   - CLCD (PORTD & PORTE)
   - Keypad (PORTB & PORTD)
   - Buzzer & Fan (PORTC)
6. Power ON and test functionality  


## 💡 Learnings

- Implemented interrupt driven timing system  
- Designed state machine for embedded control  
- Interfaced keypad and LCD with PIC  
- Built real time user interaction system  

---

## 📎 Author

Jayesh Jagtap
