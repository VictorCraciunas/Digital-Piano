# Digital Piano Project

## Overview
This project is a **Digital Piano** built using an **Arduino microcontroller** and various electronic components, such as sensors and actuators. The goal is to create a system that produces sound based on distance measurements and user input.

## Features
- **Distance-based sound generation** using an **HC-SR04 Ultrasonic Sensor**
- **Tone variation** with a **Passive Buzzer**
- **LCD Display with I2C Converter** to show real-time information
- **Adjustable LCD brightness** using a **Potentiometer**
- **Modular implementation** for easy expansion and future improvements

## Components Used
### 1. **HC-SR04 Ultrasonic Distance Sensor**
- Measures distance between **2 cm to 400 cm**
- Uses SONAR technology for distance calculation

### 2. **Passive Buzzer**
- Allows dynamic tone generation using square wave signals
- Used for producing musical notes

### 3. **PCF8574A LCD – I2C Converter**
- Simplifies LCD display integration with Arduino using I2C
- Reduces wiring complexity

### 4. **Potentiometer (50kOhm)**
- Controls LCD brightness
- Helps manage power efficiency

## Implementation Steps
### **1. Setting up the Distance Sensor**
- Measure distance in real time
- Convert distance to musical notes

### **2. Implementing the Buzzer**
- Generate different tones based on distance
- Map distance to musical frequency

### **3. Adding the LCD Display**
- Display real-time sensor readings
- Show feedback about active notes

### **4. Implementing the Potentiometer**
- Adjust LCD backlight for visibility
- Optimize user experience

### **5. Integrating the Measuring Board**
- Connect all components securely
- Ensure accurate signal transmission

### **6. Finalizing the Product**
- Optimize code and circuit for stability
- Test different functionalities

## Code Snippets
The Arduino code handles:
- **Sensor data acquisition**
- **Sound generation logic**
- **LCD output management**
- **Brightness control**

## Future Improvements
- Add **more musical notes and octaves**
- Implement **switches for octave selection**
- Display additional real-time data on the LCD

