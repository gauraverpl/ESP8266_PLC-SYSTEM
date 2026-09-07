# ESP8266_PLC-SYSTEM
This project transforms an ESP8266 (NodeMCU) into a compact, low-cost Programmable Logic Controller (PLC) equipped with wireless monitoring and control capabilities.small-scale industrial control, and IoT applications, this system bridges traditional ladder logic execution with modern web-based telemetry.  By leveraging OpenPLC Runtime ..

The ESP8266 PLC System is a microcontroller-based automation system designed to control electrical loads automatically according to temperature, ultrasonic level, and preset timing conditions.

The ESP8266 acts as the main PLC controller. The DHT11 temperature sensor continuously measures temperature, while the HC-SR04 ultrasonic sensor measures the distance/level of the material or liquid.

A timer/RTC system allows the user to operate a relay for a specific period. The four-channel relay module provides independent control of four devices such as a pump, fan, motor, light, or other electrical loads.

# Example Automation

For example:

Relay 1: Water pump
Relay 2: Cooling fan
Relay 3: Motor
Relay 4: Auxiliary load

If the ultrasonic sensor detects a low water level, the ESP8266 can turn Relay 1 ON.

If the temperature becomes higher than the programmed limit, Relay 2 can turn ON to operate a cooling fan.

If a preset timer reaches zero, the corresponding relay can automatically turn OFF, and the buzzer can sound.

This makes the system similar to a small programmable industrial PLC, while using ESP8266 as the controller.


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

