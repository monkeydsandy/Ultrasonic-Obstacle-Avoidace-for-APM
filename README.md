Ultrasound Obstacle Control


The following code has been made for an Arduino board. It uses the "NewPing" library to measure the distance of 5 ultrasound sensors HC-SR04. 4 Sensors to measure lateral distances and one to measure height. If the lower sensor measures more than 1.5 meters, the control begins to act. If one of the side sensors measures a distance of less than 1.5 meters, it sends a MAVLINK command from RCOverride, which overwrites the entries that the APM receives from the flight controller.