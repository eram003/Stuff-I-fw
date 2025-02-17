### Joystick smth bro idk

### Components
- **RC522 RFID Module**
- **Joystick Module**
- **4-digit 7-segment Display (TM1637)** or LED matrix
- **Active Buzzer**
- **Arduino Board**

### Wiring
| Component  | Connection |
|------------|-----------|
| RFID SS    | D10       |
| RFID RST   | D9        |
| Joystick X | A0        |
| Joystick Y | A1        |
| Display CLK | D2       |
| Display DIO | D3       |
| Buzzer     | D7        |

### How to Play
1. Scan the RFID.
2. If authorized, a puzzle starts on the display.
3. Solve the puzzle using the joystick.
4. Success unlocks access, failure resets the game.

### Usage
- Upload `RFID_Joystick_Game.ino` to your Arduino.
- Monitor the display for game status.
- Use the joystick to complete the challenge.

---

## Joystick-RGB Match Game

### Components
- **RGB LED**
- **4-digit 7-segment Display (TM1637)**
- **Joystick Module**
- **Arduino Board**

### Wiring
| Component  | Connection |
|------------|-----------|
| Joystick X | A0        |
| Joystick Y | A1        |
| Red LED    | D9        |
| Green LED  | D10       |
| Blue LED   | D11       |
| Display CLK | D2       |
| Display DIO | D3       |

### Usage
- Upload `Joystick_RGB_Game.ino` to your Arduino.
- Observe the display for target color values.
- Use the joystick to adjust the LED color.

---

## Multi-Sensor Dashboard

### Components
- **DHT11 Temperature & Humidity Sensor**
- **LM35 Temperature Sensor**
- **Photoresistor (LDR)**
- **1602 LCD Display**
- **Arduino Board**

### Wiring
| Sensor     | Connection |
|------------|-----------|
| DHT11      | D8        |
| LM35       | A0        |
| LDR        | A1 (with 10kΩ resistor) |
| LCD        | 7, 6, 5, 4, 3, 2 |

### How It Works
- The system continuously reads data from the sensors.
- The LCD alternates between temperature, humidity, and light readings.
- Useful for basic environmental monitoring.

### Usage
- Upload `Multi_Sensor_Dashboard.ino` to your Arduino.
- View real-time sensor data on the LCD.

---

### Notes
- Ensure all libraries (`TM1637Display`, `DHT`, `MFRC522`, etc.) are installed.
- Modify the code if needed to adjust thresholds or features.

