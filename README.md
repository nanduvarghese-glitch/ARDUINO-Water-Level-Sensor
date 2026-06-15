# ARDUINO-Water-Level-Sensor
# Water Level Monitoring System using Arduino

## Project Overview

This project is a simple Water Level Monitoring System developed using an Arduino and a Water Level Sensor. The system continuously measures the water level and displays the status (Low, Medium, or High) through the Serial Monitor. An optional buzzer can be used to alert users when the water level falls below a predefined threshold.

## Objectives

* Monitor water levels in tanks, reservoirs, or containers.
* Provide real-time water level information.
* Generate an alert when the water level is low.
* Demonstrate the use of sensors and Arduino programming in automation projects.

## Components Required

* Arduino Uno
* Water Level Sensor
* Buzzer (Optional)
* Breadboard
* Jumper Wires
* USB Cable

## Hardware Connections

### Water Level Sensor

| Sensor Pin | Arduino Pin |
| ---------- | ----------- |
| VCC        | 5V          |
| GND        | GND         |
| Signal     | A0          |

### Buzzer (Optional)

| Buzzer Pin   | Arduino Pin |
| ------------ | ----------- |
| Positive (+) | D8          |
| Negative (-) | GND         |

## Working Principle

1. The water level sensor detects the amount of water present.
2. The Arduino reads the sensor value through the analog input pin (A0).
3. Based on the sensor reading:

   * Low Water Level: Sensor value less than 300.
   * Medium Water Level: Sensor value between 300 and 599.
   * High Water Level: Sensor value 600 or above.
4. The status is displayed on the Serial Monitor.
5. If the buzzer is connected, it activates when the water level is low.

## Software Requirements

* Arduino IDE
* Arduino Uno Board Package

## Code Features

* Reads analog values from the water level sensor.
* Displays water level values on the Serial Monitor.
* Categorizes water level into Low, Medium, and High.
* Supports buzzer alerts for low water conditions.

## Applications

* Household water tank monitoring.
* Agricultural irrigation systems.
* Industrial water storage monitoring.
* Smart water management systems.
* Educational Arduino projects.

## Advantages

* Low cost and easy to implement.
* Real-time monitoring.
* Expandable for IoT applications.
* Simple hardware requirements.

## Future Enhancements

* LCD display for local monitoring.
* IoT integration using ESP8266/ESP32.
* Mobile app notifications.
* Automatic water pump control.
* Cloud-based data logging and analysis.

## Conclusion

The Water Level Monitoring System provides an efficient and cost-effective solution for monitoring water levels. It can be easily extended with additional features such as automatic pump control, wireless monitoring, and IoT connectivity, making it suitable for both educational and practical applications.
