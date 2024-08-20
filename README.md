Early Flood detection and avoidance using Arduino
Project circuit diagram : {refer this (link) circuit diagram for connections}

(https://user-images.githubusercontent.com/99020701/212123257-ad2f3fb3-e8cb-4e6c-955e-7395e5292b0a.jpg)

Methodology :

Dams are built all around the world primarily for irrigation, power generating, and flood control. While the first two tasks are acknowledged, dams' involvement in flood management has generally been underestimated. Unfortunately, flood control is entirely ignored in both irrigation and hydroelectric projects. Authorities always aim to save as much water as possible in reservoirs during the monsoon season, which is then used for irrigation and energy generating throughout the summer months. It is a globally known practise to keep a reservoir's water level below a specified level before the start of the monsoon season. This is done so that when the monsoon rains arrive, there is enough space to retain the excess rainfall and so that water may be released in a controlled manner, preventing flooding downstream when the dams are overflowing. Overflowing dam could result in major destruction of the dam and flood in villages near the bank of the river which means major threats to human life and wildlife. Today most of dams in India uses manual ways of detecting water level. They use water level marking on the dam’s walls to major the level of water in dam. This manual way leads to human errors and some time to major destruction. To handle this destruction, we have implemented this on a dam model. Here we are trying to automate dams so that dams can detect water level and automatically release excess water that could leads to dam’s overflow. One of the main reasons of human death due to floods is because of the late alert to peoples living on the banks of the river in which dam is constructed. To overcome this, we have used GSM module which will send alert SMS to them to evacuate the area. We have use following sensors to evaluate the current water level and situation of the dam.

Arduino uno
Ultrasonic sensor (to measure water level)
Servo motor (to operate dam gate)
LM-35 Temperature sensor (to measure temperature)
Moisture sensor (to measure soil water holding capacity)
Float sensor (to measure blue line)
GSM module (to send alert SMS)
