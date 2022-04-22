### 1. Block Diagram and Explanation
# 1a. Block Diagram
![Screenshot (15)](https://user-images.githubusercontent.com/102345521/164744344-a83986a8-fc2d-4a2f-9462-2f3919bfcbd7.png)
## 1b. SENSORS
* Temperature Sensor (Thermistor) or Potentiometer
. This Thermistor is a resistor whose resistance is dependent on temperature here this change in resistence produces change in voltage, this voltage is taken as input to micro controller.
* PushButton:
. Provides an interface to increase or decrease temperature.
## 1c. ACTUATORS
* LCD Display:
. Displays each and every value we enter in our Push button along with Temperature.
.. Relay:
. It will act as a Mechanical switch whenever your set point reached my the heater the relay will cut the circuit until it gets cool
## 1d. MICRO CONTROLLER AND ARDUINO
* MicroController:
. In general we used here ATMEGA 328 its is just as brain to entire circuit
. This is the main component which controls all the above mentioned part or thins of our embedded system.This interfaces Pushbuttons and LCD and controls the heater.
# 2. Architecture
.. Behavioural Diagrams
. 2a. High Level Flow chart Behavioural Diagram
![Screenshot (17)](https://user-images.githubusercontent.com/102345521/164745679-960f0a8c-d2b9-484c-b264-fb97f41b8cbc.png)
. 2b. Low Level Flow chart Behavioural Diagram 
![Screenshot (19)](https://user-images.githubusercontent.com/102345521/164746090-1d6c5bd5-c7fb-46eb-91fe-388d879f51cc.png)
. Structural Diagrams
. 2c. High Level UML Use Case Structural Diagram
![Screenshot (21)](https://user-images.githubusercontent.com/102345521/164746496-68493352-5b95-4816-9775-64874f7ac3b7.png)
## Best Methods to be Followed
* Exact Mapping of code to avoid confusions
* Mentioning of both High level and Low level Behavioral and structural diagrams for better  understanding
* Followed the exact symbols to make the understanding easier
* Detailed explanation in Low level Behavioural and Structural Diagrams
