IOT-Early Flood Detection and Avoidance
Project Overview
This project aims to automate flood control in dams using an array of sensors and an Arduino UNO microcontroller. Traditional manual methods for monitoring water levels in dams can lead to human errors and potential flooding disasters. This automated system enhances flood management by integrating real-time measurements and control mechanisms to prevent overflow and mitigate risks to human life and property.

Features
Water Level Monitoring: An ultrasonic sensor measures the water level in the dam. If the water level exceeds 95% of the dam’s capacity, a servo motor-operated gate opens to release excess water, preventing overflow.
Flood Alert System: A float sensor in a model river detects high water levels, triggering a buzzer and sending SMS alerts via a GSM module to evacuate nearby areas.
Soil and Temperature Monitoring: A moisture sensor gauges the soil’s water-holding capacity, and an LM-35 temperature sensor estimates evaporation rates.
Rainfall Prediction: Machine learning models predict the next day’s rainfall, adjusting the dam’s water levels proactively to prevent overflow.
Real-Time Adjustments: Manual input for predicted rainfall is used to adjust the ultrasonic sensor’s thresholds, ensuring timely gate operations.
Components
Arduino UNO: Central microcontroller for system integration and control.
Ultrasonic Sensor: Measures the dam’s water level.
Servo Motor: Controls the dam gate to release excess water.
LM-35 Temperature Sensor: Measures ambient temperature.
Moisture Sensor: Assesses soil water-holding capacity.
Float Sensor: Monitors water levels in the river model.
GSM Module: Sends SMS alerts for flood warnings.
Installation & Usage
Connect all sensors and modules to the Arduino UNO according to the provided schematic.
Upload the Arduino code to the microcontroller.
Input the predicted rainfall values into the serial monitor.
Monitor real-time water levels and adjust system settings as needed.
Future Enhancements
Integration of advanced machine learning models for more accurate rainfall predictions.
Expansion of the system to handle larger-scale flood management.
Repository
Code: Available in the src directory.
Documentation: Detailed setup and usage instructions in the docs directory.
For further information, please refer to the README and project documentation.
