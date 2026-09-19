# arduino-lcd-and-simple-calculator
Arduino projects using a 16×2 LCD display, including LCD interfacing, text display, cursor control, and a simple calculator for performing basic arithmetic operations.
Arduino LCD and Simple Calculator

This repository contains my Arduino experiments with a 16×2 LCD display, covering LCD interfacing and a simple calculator that performs basic arithmetic operations.

📌 What I Learned

- Interfacing a 16×2 LCD with Arduino UNO
- Understanding LCD pins and their functions
- Using the "LiquidCrystal" library
- Displaying text and numbers on the LCD
- Using "lcd.setCursor()" to control the cursor position
- Clearing and updating the LCD display
- Taking numerical input through Serial Monitor
- Performing basic arithmetic operations using Arduino
- Handling Serial input and buffer issues

🧮 Simple Calculator

The calculator takes:

1. First number
2. Second number
3. Arithmetic operator

It supports:

- Addition "+"
- Subtraction "-"
- Multiplication "*"
- Division "/"

The calculated result is displayed on the 16×2 LCD.

🔌 LCD Connections

LCD Pin| Function| Arduino
RS| Register Select| D7
E| Enable| D8
D4| Data| D9
D5| Data| D10
D6| Data| D11
D7| Data| D12

🛠️ Components Used

- Arduino UNO
- 16×2 LCD Display
- Breadboard
- Jumper Wires
- USB Cable

📚 Arduino Concepts Used

LiquidCrystal Library
lcd.begin()
lcd.print()
lcd.setCursor()
lcd.clear()
Serial.begin()
Serial.available()
Serial.parseFloat()
Serial.read()

⏯️ Demo-Video;
1. Basic_LCD: "https://drive.google.com/file/d/1j7OpyiG2PZQAJuKQletXWQENqlBlxOB6/view?usp=drivesdk"
2. Simple_Calculator_LCD:
"https://drive.google.com/file/d/1UV9m0dc5jtn-Z_D7WHXqfb-ezr_N16fi/view?usp=drivesdk"

🎯 Purpose

This project helped me understand how an Arduino can communicate with an LCD and display useful information while also taking input through the Serial Monitor.

It is another step in my ongoing Arduino and Embedded Systems learning journey.

---
