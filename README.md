# Sonar-Radar-IOT-PROJECT-
I have prepared this project during 4th semester for the subject Embedded System 

###Overview
The Sonar Radar project is an IoT application that utilizes an Arduino microcontroller and ultrasonic sensors to detect objects and measure distances. The data collected can be transmitted over the Internet, allowing for remote monitoring and control.

###Features
• Distance Measurement: Accurately measures the distance to nearby objects using ultrasonic technology.
• Real-Time Data Transmission: Sends distance data over the Internet using a Wi-Fi module.
• User Interface: Displays measurements on an LCD screen or a web application.
• Alert System: Triggers notifications when objects are detected within a specified range.
Components
• Arduino Board: The main microcontroller
• Ultrasonic Sensor: HC-SR04 or similar for distance measurement.
• Power Supply: To power the Arduino and sensors.

VCC to 5V
GND to Ground
Trigger pin to a digital pin
Echo pin to another digital pin
Connect the Wi-Fi module to the Arduino:

VCC to 3.3V
GND to Ground
TX to RX pin on Arduino
RX to TX pin on Arduino
Ensure the power supply is connected properly.


##Usage
The Sonar Radar can be used in various applications such as:
• Obstacle detection for robots.
Parking assistance in vehicles.
• Security systems for monitoring restricted areas.
• Smart home automation for detecting presence.

###Future Enhancements
• Implement data logging for historical analysis.
• Develop a mobile application for real-time notifications.
• Integrate with additional sensors for comprehensive monitoring.
