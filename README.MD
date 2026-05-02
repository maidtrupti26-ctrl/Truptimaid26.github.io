Title:-
     AI Based Smart Fault Detection System

Introduction:-
           This project uses ESP32 to monitor voltage and current in real-time.
           It detects faults automatically and displays data on a web dashboard.

Components Used:-
ESP32
Voltage Sensor
Current Sensor
LED Indicator
WiFi Network


Features:-

Real-time monitoring

Fault detection system

Web-based dashboard

LED alert system


 Working:-

The ESP32 reads voltage and current values using sensors.
If voltage < 10V OR current < 0.05A → Fault detected.
Otherwise system is normal.


🌐 Output

Web page shows:

Voltage

Current

Status (Normal / Fault)
#Future Scope
- Mobile app integration
- SMS alert system
- Cloud data storage


📂 Files
