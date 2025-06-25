# 🎮 Retro Gaming Console using ARM Microcontroller

A retro-style embedded gaming system developed as part of the ARM Laboratory (EC39006) course at KIIT, Spring 2024–25. This project implements classic arcade games like Ping Pong, Snake, and Brick Breaker using a graphical LCD, rotary encoder, and an Arduino-compatible microcontroller.

---

## 🧠 Objective

To design and implement a gaming console on embedded hardware, leveraging low-level ARM programming concepts such as GPIO, interrupt handling, and graphical output.

---

## 🛠️ Hardware Components

- Microcontroller (Arduino UNO or compatible)
- Graphical LCD (128x64 ST7920)
- Rotary Encoder with Push Button
- Connecting wires and resistors
- Power Supply

---

## 🧰 Software Tools

- Arduino IDE  
- U8glib graphics library  
- Embedded C / Assembly (ARM concepts applied)  

---

## 📋 Features

- 📜 Menu Navigation using a rotary encoder
- 🏓 Ping Pong: Classic paddle game with AI
- 🐍 Snake: Retro snake game with random food generation
- 🧱 Brick Breaker: Ball-based brick smashing game with realistic collisions
- 👥 Fade-in Team Credits Animation on startup
- 🎮 Debounced button inputs and encoder-based controls

---

## 💡 Core Concepts Demonstrated

- SPI communication with graphical LCD  
- Rotary encoder input processing with interrupts  
- State management using enums  
- Game loop rendering using `u8g.firstPage()/nextPage()`  
- Memory-safe and user-friendly C programming  
- Team display animations and modular game design  

---

## 🧑‍💻 Team Members

- Vaibhav Jain – 2228077  
- Vineet Gupta – 2228079  
- Sumit Sahu – 2228074  
- Shaivee Sahu – 2228058  
- Shreya Mallik – 2228062  

---

## 📈 Future Improvements

- Add sound via buzzer
- Store high scores in EEPROM
- Improve paddle AI using adaptive difficulty
- Include new mini-games with advanced animations

---

## 📜 License

This project is released under the [MIT License](LICENSE).
