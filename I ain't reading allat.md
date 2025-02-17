- RC522 RFID module <br/>
SDA → D10  
SCK → D13  
MOSI → D11  
MISO → D12  
IRQ → Not connected  
GND → GND  
RST → D9  
3.3V → 3.3V
  
- 5V Relay
Relay IN → D8
VCC → 5V
GND → GND

- Jumper wires
- 9V battery
- LED

### Joystick smth bro idk

### Components
- **RC522 RFID Module**
- **Joystick Module**
- **4-digit 7-segment Display (TM1637)** or LED matrix
- **Active Buzzer**
- **Arduino Board**

### Arddszzsa
| Component  | Connection |
|------------|-----------|
| RFID SS    | D10       |
| RFID RST   | D9        |
| Joystick X | A0        |
| Joystick Y | A1        |
| Display CLK | D2       |
| Display DIO | D3       |
| Buzzer     | D7        |

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

### Adrasdfrv
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

### Ard
| Sensor     | Connection |
|------------|-----------|
| DHT11      | D8        |
| LM35       | A0        |
| LDR        | A1 (with 10kΩ resistor) |
| LCD        | 7, 6, 5, 4, 3, 2 |

### Wiki ahh
- The system continuously reads data from the sensors.
- The LCD alternates between temperature, humidity, and light readings.
- Useful for basic environmental monitoring.

### Usage
- Upload `Multi_Sensor_Dashboard.ino` to your Arduino
- View real-time sensor data on the LCD.

---

### yes
- make sure the libraries (`TM1637Display`, `DHT`, `MFRC522`, etc.) are installed.
- Modify the code if needed to adjust thresholds or features.

