# <b><ul>Patient_Health_Monitoring_System </ul></b>
IoT-based Smart Patient Health Monitoring System designed for real-time monitoring of ECG signals and heart rate remotely through cloud connectivity.

The system uses an AD8232 ECG module to acquire heart electrical activity and a pulse sensor for BPM measurement. Since the ESP8266 internal ADC has low resolution and WiFi noise issues, I used the ADS1115 external 16-bit ADC for accurate ECG signal conversion through I2C communication.

The ESP8266 NodeMCU acts as the central controller and transmits the patient data over WiFi using the MQTT protocol to a web dashboard for real-time monitoring. LEDs are used for patient status indication and alert generation.

This project combines embedded systems, biomedical signal acquisition, IoT communication, MQTT protocol, and real-time cloud monitoring.”
<br>IoT Based Smart Patient Health Monitoring System<br>
<br>Developed a real-time IoT healthcare monitoring system using ESP8266 NodeMCU.<br>
<br>Implemented ECG monitoring using AD8232 ECG sensor module.<br>
<br>Integrated ADS1115 16-bit ADC for high-resolution ECG acquisition.<br>
<br>Designed MQTT-based wireless communication for remote monitoring.<br>
<br>Implemented pulse sensor-based BPM monitoring and alert indication system.<br>
<br>Worked with I2C communication, sensor interfacing, and real-time data visualization.<br>
