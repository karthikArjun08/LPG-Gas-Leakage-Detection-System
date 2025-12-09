LPG Gas Leakage Detection System using MQ-2 & Arduino Uno

This project is a simple and effective LPG Gas Leakage Detection System built using the MQ-2 gas sensor, Arduino Uno, LED, and buzzer.
When LPG concentration crosses a safe threshold, the system triggers visual and audible alerts.


🔥 Features

Continuous LPG gas monitoring

Real-time analog value reading

LED alert indicator

Audible buzzer alarm

Adjustable gas detection threshold

Beginner-friendly circuit & code


🧩 Components Used

Arduino Uno

MQ-2 Gas Sensor

Buzzer

LED (with 220Ω resistor)

Jumper wires

Breadboard


🔌 Circuit Diagram

Arduino 5V ----- MQ2 VCC  
Arduino GND ---- MQ2 GND  
Arduino A0 ----- MQ2 A0  

Arduino D13 ---- LED (via 220Ω resistor) ---- GND  
Arduino D12 ---- Buzzer ---- GND  


🧠 How It Works

MQ-2 sensor measures gas concentration.

Arduino reads the analog value and compares it with a threshold.

If dangerous levels are detected:

🔴 LED turns ON

🔊 Buzzer sounds an alarm

All readings are printed in the Serial Monitor for debugging & calibration.
