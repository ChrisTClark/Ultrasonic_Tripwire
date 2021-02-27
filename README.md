# Ultrasonic_Tripwire #
Ultrasonic Tripwire, wireless communication to voice alert

# Desired End State #

A voice alert, specific to the sensor/location, is announced with the sensor is tripped. The sensor is located at a certain location in the house, where the condition may occur that is to be alerted. When the sensor is tripped, a wireless signal is sent to the master receiver located centrally in the home. The master receiver, when receiving this signal, initiates the voice alert. 

The desired location is along the railing of the upstairs bannister, so as to be triggered when sensor beam (along the rail) is broken. 

# Requirements #

1. Sensor triggers when Jude commences to scale the bannister, as if to climb over it. 
2. Voice alert that is loud enough to be heard throughout the downstairs area, and announces the specific condition that occurred, such as "Jude is on the upstairs bannister". 
3. Wireless transmission from sensor to master receiver. 

# Repository Structure #

1. Project: There is one project associate with this repository. It is used to manage the work/issues.
3. Issues: Work is broken down into issues, and managed through the project kanban board.
4. Code: there are three main sections of code. Each section is dedicated to a single piece of hardware to upload. 

# Hardware #

There are three hardware components with distinct codes for upload into each. 
* Sensor: One battery-powered Arduino with HC-SR04 Ultrasonic sensor and LRFL2401 Transceiver (transmitting sensor information). 
* Master Receiver: Plug-in Arduino with LRFL2401 Transceiver (acting as receiver to the Ultrasonic Sensor). 
* Voice Alert: Plug-in Arduino, wired to the Main Receiver with SD card reader and speaker. 
