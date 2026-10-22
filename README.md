# ESP32 HC-SR04

An ESP32 project that uses an HC-SR04 ultrasonic sensor to measure distance.

## How It Works

The HC-SR04 sensor sends an ultrasonic pulse and measures how long it takes to return.  
The ESP32 calculates the distance based on that time.

## Components

- ESP32 development board
- HC-SR04 ultrasonic sensor
- Jumper wires
- Breadboard

## Wiring

| HC-SR04 Pin | ESP32 Pin |
|---|---|
| VCC | 5V |
| GND | GND |
| TRIG | GPIO 5 |
| ECHO | GPIO 18 |

> Update the GPIO pins if your code uses different ones.

## How to Run

1. Open the project in VS Code with PlatformIO.
2. Connect the ESP32 to your computer.
3. Build and upload the project.
4. Open the Serial Monitor.
5. Set the baud rate to `115200`.
6. View the measured distance in centimeters.

## Example Output

```text
Distance: 23.4 cm
Distance: 24.1 cm
Distance: 25.0 cm
```

## Author

Created by [Alan Besic](https://github.com/abesic1).
