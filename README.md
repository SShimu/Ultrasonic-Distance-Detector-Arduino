
# Ultrasonic Distance Detector with Arduino

An embedded system that measures precise distances (2 cm – 4 m) using an **HC-SR04 ultrasonic sensor** and **Arduino Uno**.  
The system calculates distance through **sound wave echo-time analysis** and displays results on an **LCD screen** or **serial monitor** in real time.


##  Features

- Accurate distance measurement from 2 cm to 400 cm  
- Real-time feedback via LCD or serial monitor  
- Compact, low-cost, and energy-efficient hardware  
- Suitable for **obstacle detection**, **proximity alerts**, and **automated parking systems**

---

##  Hardware Components

| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino Uno | 1 | Microcontroller board |
| HC-SR04 Ultrasonic Sensor | 1 | Measures distance via ultrasonic waves |
| 16×2 LCD Display | 1 | Displays distance readings |
| Breadboard & Jumper Wires | — | For circuit connections |
| Potentiometer (optional) | 1 | For LCD contrast control |

---

##  Circuit Connections

| HC-SR04 Pin | Arduino Pin |
|--------------|-------------|
| VCC | 5V |
| GND | GND |
| TRIG | Digital Pin 9 |
| ECHO | Digital Pin 10 |
