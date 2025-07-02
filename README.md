Company Name: CODTECH IT SOLUTIONS
INTERN ID: CT06DG486
DOMAIN: EMBEDDED SYSTEMS
DURATION: 6 weeks
MENTOR: NEELA SANTOSH
# Push Button Counter
This project is a **Push Button Counter** designed and simulated using Wokwi, an online platform for simulating embedded systems. The main objective is to create a simple digital counter that increments each time a push button is pressed, helping beginners understand how to handle digital inputs, implement debouncing, and interact with the serial monitor.

# Overview
A push button is connected to a microcontroller (ESP32 or Arduino Uno). Every time the button is pressed, a counter variable is incremented, and the updated count is displayed on the serial monitor. The circuit is designed using an internal pull-up configuration to ensure stable button readings and reduce wiring complexity. Additionally, a debounce delay is added to avoid multiple counts due to mechanical noise.

# Simulation Platform
The entire project was simulated on **Wokwi**, a powerful and easy-to-use online simulator that allows you to build and test microcontroller circuits virtually. It helps you understand the real-time interaction between hardware and code without needing physical components.  



# Applications
Production counters: Count objects passing on a conveyor belt.
Event entry systems: Count visitors entering or exiting a hall.
Voting devices: Register individual votes via button presses.
Scoreboards: Track points manually in sports or small competitions.
Fitness counters: Count exercise repetitions or cycles.

# Educational Importance
This project serves as a foundation for learning embedded systems concepts:
- Understanding digital inputs and the use of pull-up resistors.
- Learning about button debounce techniques.
- Practicing serial communication and debugging using the serial monitor.
- Gaining confidence in writing basic logic for microcontroller applications.

# Possible Extensions
- Display count on an LCD instead of serial monitor.
- Add a **reset button** to set the count back to zero.
- Implement a decrement button to reduce the count.
- Include a buzzer or LED indicator for feedback on button press.
- Store count value in EEPROM for persistence after power-off.

# How it works
- The button is configured as `INPUT_PULLUP`, so it remains HIGH when not pressed and reads LOW when pressed.
- Every time a falling edge (HIGH to LOW) is detected, the counter increments.
- A small delay  is added to avoid false triggers (debouncing).
- 
# Simulation Output
![Image](https://github.com/user-attachments/assets/d243b72a-e6c4-4844-84a2-d18b29f5a541)



