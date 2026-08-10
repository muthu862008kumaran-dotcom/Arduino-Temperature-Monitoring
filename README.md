# Arduino-Temperature-Monitoring
Arduino-based temperature monitoring system using an      DS18B20 Sensor and 16x2 I2C LCD. It displays real-time temperature readings and sends data to the Serial Monitor.
Room Temperature Monitoring using Arduino

Objective

To measure room temperature using a DS18B20 temperature sensor and display the current temperature on a 16×2 I2C LCD.

Components

- Arduino UNO
- DS18B20 temperature sensor
- 16×2 I2C LCD
- 4.7kΩ resistor
- Jumper wires
- Breadboard

Connections

DS18B20

- VCC → Arduino 5V
- GND → Arduino GND
- DQ → Arduino D2
- 4.7kΩ resistor → between DQ and VCC

16×2 I2C LCD

- VCC → Arduino 5V
- GND → Arduino GND
- SDA → Arduino A4
- SCL → Arduino A5

Working

The DS18B20 sensor measures the room temperature and sends the temperature data to the Arduino UNO. The Arduino processes the sensor reading and displays the current temperature on the 16×2 I2C LCD.

Result

The room temperature was successfully measured using the DS18B20 sensor and displayed on the 16×2 I2C LCD.