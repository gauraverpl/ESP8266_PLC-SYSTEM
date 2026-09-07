# ESP8266_PLC-SYSTEM
This project transforms an ESP8266 (NodeMCU) into a compact, low-cost Programmable Logic Controller (PLC) equipped with wireless monitoring and control capabilities.small-scale industrial control, and IoT applications, this system bridges traditional ladder logic execution with modern web-based telemetry.  By leveraging OpenPLC Runtime ..

# COMPONNET LIST 

🌡️ Temperature sensor

📏 Ultrasonic sensor for level/distance

⏱️ Timer control

🔔 Buzzer

🔌 4-channel relay

📟 16×2 LCD

🎛️ Local control/status display

⚙️ Automatic ON/OFF logic




| Component          | Name                           | Purpose                                           |
| ------------------ | ------------------------------ | ------------------------------------------------- |
| Controller         | **ESP8266 NodeMCU / WROOM-02** | Main PLC controller                               |
| Temperature sensor | **DS18B20**                    | Measures temperature                              |
| Ultrasonic sensor  | **HC-SR04**                    | Measures tank/object distance                     |
| Display            | **16×2 LCD**                   | Displays temperature, level, timer & relay status |
| Timer/RTC          | **DS3231 RTC**                 | Accurate real-time timer                          |
| Relay 1            | **Relay Module CH1**           | Load/device 1                                     |
| Relay 2            | **Relay Module CH2**           | Load/device 2                                     |
| Relay 3            | **Relay Module CH3**           | Load/device 3                                     |
| Relay 4            | **Relay Module CH4**           | Load/device 4                                     |
| Alarm              | **5V Buzzer**                  | Alarm/notification                                |
| Power              | **5V regulated supply**        | ESP8266 + modules                                 |

