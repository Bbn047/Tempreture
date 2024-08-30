Libraries Required
Ensure the following libraries are installed in your Arduino IDE:

Wire.h (comes pre-installed)
LiquidCrystal_I2C.h
Adafruit_GFX.h
Adafruit_SSD1306.h
DHT.h


Pin Connections:

DHT11 Sensor:
Data Pin -> Arduino Digital Pin 2
VCC -> 5V
GND -> GND

SSD1306 OLED Display:
SDA -> Arduino SDA (A4 on Uno/Nano)
SCL -> Arduino SCL (A5 on Uno/Nano)
VCC -> 3.3V
GND -> GND

16x2 I2C LCD Display:
SDA -> Arduino SDA (A4 on Uno/Nano)
SCL -> Arduino SCL (A5 on Uno/Nano)
VCC -> 5V
GND -> GND

Red LED:
Anode (+) -> Arduino Digital Pin 9
Cathode (-) -> GND (via a current-limiting resistor)

Green LED:
Anode (+) -> Arduino Digital Pin 8
Cathode (-) -> GND (via a current-limiting resistor)
