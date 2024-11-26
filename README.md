**Project Overview**

The Smart Street Lighting System is designed to enhance energy efficiency and automate street lighting using sensors. The system uses an LDR (Light Dependent Resistor) to measure ambient light and IR sensors to detect the presence of vehicles or pedestrians. Based on the sensor readings, the system dynamically adjusts the brightness of streetlights, reducing energy consumption when the streets are empty.


**Features**

Automatic Light Control: Lights turn ON/OFF based on ambient light and motion detection.
Energy Efficiency: Lights dim when the area is unoccupied.
Sensor-Based Automation:
IR Sensors detect motion.
LDR measures light intensity.
Customizable Brightness Levels: Lights are dimmed or brightened based on specific conditions.

**Components Used**

Component	Quantity

Arduino UNO	1

IR Sensors	3

LDR Sensor	1

LEDs (Streetlights)	3

Resistors	As required

Jumper Wires	As required

Breadboard	1


**Circuit Diagram**

![image](https://github.com/user-attachments/assets/7ca10ff1-655f-45ba-9ff0-7f1499de64a2)


**Code**

The complete code for the project is available in the code/ directory of this repository.

**Setup and Working
Hardware Setup**

Connect the IR sensors to pins 8, 12, and 13 of the Arduino.

Connect the LDR to pin 7.

Connect the LEDs to pins 3, 5, and 6 with appropriate resistors.

Power the Arduino via USB or an external power source.

**Software Setup**

Install the Arduino IDE from here.

Clone this repository or download the code.

Open the .ino file in the Arduino IDE.

Upload the code to the Arduino board.
