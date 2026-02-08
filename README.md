# Smart Desk Monitor (Temp & Humidity)

A practical Arduino-based environmental monitor that tracks real-time temperature and humidity to optimize study conditions.

## 🚀 Features
- **Real-time Monitoring:** Uses a DHT11 sensor for accurate environmental data.
- **Smart Feedback:** Provides contextual suggestions (e.g., "Perfect Study!" or "Drink Water!") based on humidity levels.
- **Portable Design:** Powered via a 9V battery for desk portability.
- **I2C Integration:** Uses an I2C LCD to keep wiring clean and efficient.

## 🛠 Materials Used
- **Microcontroller:** Arduino Uno R3
- **Sensor:** DHT11 (Temperature & Humidity)
- **Display:** 16x2 I2C LCD
- **Power:** 9V Battery with DC Jack

## 🔌 Wiring Diagram
| Component | Pin | Arduino Pin |
| :--- | :--- | :--- |
| DHT11 | Data | Pin 2 |
| LCD | SDA | A4 |
| LCD | SCL | A5 |
| All | VCC/GND | 5V/GND |

## 💻 Setup
1. Install the `DHT sensor library` and `LiquidCrystal I2C` library in the Arduino IDE.
2. Update the I2C address in the code (default is `0x27`).
3. Upload the code found in `/src`.
