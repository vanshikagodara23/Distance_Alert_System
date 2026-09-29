# Distance Alert System

Distance alert system using an HC-SR04 ultrasonic sensor and an RGB LED. The LED changes colour as an object gets closer.

## How it works

| Distance | LED colour | Meaning |
|---|---|---|
| More than 30 cm | Green | Safe |
| 10 – 30 cm | Yellow | Warning |
| Less than 10 cm | Red | Very close |

The measured distance is also printed on the Serial Monitor (9600 baud).

## Components

- Arduino Uno (or compatible)
- HC-SR04 ultrasonic sensor
- RGB LED (common cathode) + 3 resistors (220 Ω)
- Jumper wires, breadboard

## Wiring

| Part | Pin | Arduino pin |
|---|---|---|
| HC-SR04 | TRIG | 9 |
| HC-SR04 | ECHO | 10 |
| RGB LED | Red | 6 |
| RGB LED | Green | 3 |
| RGB LED | Blue | 5 |
| HC-SR04 | VCC / GND | 5V / GND |

## How to run

1. Open `Distance_Alert_System.ino` in the Arduino IDE.
2. Select your board and port.
3. Upload, then open the Serial Monitor at 9600 baud.
