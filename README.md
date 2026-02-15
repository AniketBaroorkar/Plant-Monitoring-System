🌱 ESP32 Smart Farming Monitor 

The ESP32 Smart Farming Monitor is an IoT-based project designed to automate and monitor key environmental conditions for plant growth. It uses an ESP32 microcontroller to read soil moisture, temperature, and humidity data, displaying real-time values on a responsive web interface. The system intelligently controls a water pump using a relay module based on soil moisture percentage, ensuring plants are watered only when needed.

🚀 Features
📶 Wi-Fi Connectivity: ESP32 connects to your local Wi-Fi to serve live sensor data on a web page.
🌡️ Temperature & Humidity Monitoring: Uses DHT11 sensor to monitor environmental conditions.
🌾 Soil Moisture Analysis: Converts analog values from YL-69 sensor to percentage-based readings.
💧 Automatic Water Pump Control: Activates pump via a relay module when moisture falls below a threshold.
🌐 Live Web Dashboard: Displays current readings with a clean, mobile-friendly UI.

🔌 Hardware Used
ESP32 Dev Module
DHT11 Temperature & Humidity Sensor
YL-69 Soil Moisture Sensor
Relay Module (1-channel)
5V DC Water Pump
Jumper Wires, Breadboard/PCB, Power Supply

🧠 How It Works
The ESP32 reads sensor data every 2 seconds.
It maps soil moisture from raw ADC (0–4095) to percentage (0–100%).
If soil moisture drops below the set threshold (e.g., 40%), the relay turns ON the pump.
The device hosts a live dashboard accessible via browser on the local network.


📸 Interface Preview
Web page shows:

🌡️ Temperature (°C)
💧 Humidity (%)
🌾 Soil Moisture (%)
