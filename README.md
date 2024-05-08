**Arduino Power Monitoring System**
This Arduino project implements a basic power monitoring system using analog sensors, an LCD display, and LED indicators. The system measures voltage, current, and calculates power consumption, displaying the results on an LCD screen and providing visual feedback through LEDs.

**Components Used**
1.Arduino Uno
2.LiquidCrystal Library (for LCD display)
3.Analog Sensors:
3.1 Voltage Sensor (connected to A1)
3.2 Current Sensor (connected to A0)
4.LEDs for Indicators:
4.1 Voltage Indicator LED (connected to pin 9)
4.2 Current Indicator LED (connected to pin 8)
4.3 Power Indicator LED (connected to pin 10)
**Calibration Factors**
1.voltageMultiplier: Calibration factor for voltage measurement
2.currentMultiplier: Calibration factor for current measurement
**Setup and Configuration**
**Connections:**
Connect the analog sensors (voltagePin and currentPin) to the respective sensors.
Connect the LED indicator pins (voltageIndicatorPin, currentIndicatorPin, powerIndicatorPin) to LEDs.
**Library Installation:**
Make sure to include the LiquidCrystal library in your Arduino IDE for the LCD display.

