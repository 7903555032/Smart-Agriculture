🌾 Smart Agriculture System using ESP32 & Blynk

An integrated IoT-based Smart Agriculture Monitoring and Automation System developed using ESP32, Blynk IoT platform, and multiple sensors for real-time monitoring and control of soil moisture, temperature, rainfall, and light conditions. The system also supports manual override via Blynk and physical button.

📌 Features
✅ Soil Moisture Monitoring & Pump Control
✅ Temperature Monitoring & Fan Control
✅ Rain Detection System
✅ Light Intensity Detection
✅ Manual/Auto Mode Toggle via Blynk & Button
✅ Real-Time Data Updates to Blynk App
✅ NPN Transistor Circuit for 5V Fan
✅ Voltage Divider Circuit for 5V Sensors Compatibility with ESP32 (3.3V)

🧠 System Overview
The project is divided into four main functional phases:

🌱 Soil Moisture Monitoring

Measures moisture and controls water pump (via relay).

Red LED & Buzzer indicate dryness; Green LED indicates adequate moisture.

Toggle between Auto & Manual modes using Blynk app (V0) or button (GPIO13).

🌡️ Temperature Monitoring

DHT11 measures temperature.

If temperature exceeds a threshold (25°C), a 5V fan is activated via NPN transistor circuit and an orange LED is lit.

🌧️ Rain Detection

Detects rainfall using analog rain sensor.

Turns on blue LED if rain is detected.

💡 Light Detection

Detects ambient light using LDR.

Turns on white LED if it is dark.
