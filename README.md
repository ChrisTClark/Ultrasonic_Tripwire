# Ultrasonic_Tripwire #
Ultrasonic Tripwire, wireless communication to voice alert

# Repository Structure #

1. Project: There is one project associate with this repository. It is used to manage the work/issues.
3. Issues: Work is broken down into issues, and managed through the project kanban board.
4. Code: there are three main sections of code. Each section is dedicated to a single piece of hardware to upload. 

# Hardware #

There are three hardware components with distinct codes for upload into each. 
* Ultrasonic Sensor: One battery-powered Arduino with HC-SR04 Ultrasonic sensor and LRFL2401 Transceiver (transmitting sensor information). 
* Main Receiver: Plug-in Arduino with LRFL2401 Transceiver (acting as receiver to the Ultrasonic Sensor). 
* Voice Alert: Plug-in Arduino, wired to the Main Receiver with SD card reader and speaker. 
