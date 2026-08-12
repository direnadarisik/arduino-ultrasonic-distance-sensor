# Arduino Ultrasonic Distance Sensor

An Arduino Uno project using an HC-SR04 ultrasonic sensor to measure distance.

## Components

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Jumper Wires

## Pin Connections

| HC-SR04 | Arduino Uno |
|---------|-------------|
| VCC     | 5V          |
| GND     | GND         |
| TRIG    | D9          |
| ECHO    | D10         |

## How It Works

The HC-SR04 ultrasonic sensor sends an ultrasonic pulse and measures the time it takes for the echo to return.

The Arduino calculates the distance and displays the result in centimeters through the Serial Monitor.

## Code

The Arduino code is available in `ultrasonic_distance.ino`.

## Author

Diren Adar Işık
