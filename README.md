# IoTBasedSmartDustbin
This is a demo project of Iot based smart waste management system.Central to the system is the integration of ultrasonic sensors, servo motors, LCD displays, a buzzer, and the Blynk platform within a smart waste bin. Upon detection of an object in proximity, the ultrasonic sensor triggers the servo motor to open the bin lid, facilitating seamless waste disposal. Simultaneously, another ultrasonic sensor measures the distance, providing real-time feedback on the garbage level, which is displayed both locally on an LCD display and remotely via the Blynk application. This enables users to conveniently monitor the fill level of the bin from anywhere, at any time, promoting proactive waste management practices.

The project description goes as follows:


![circuitsetup1](https://github.com/Tama-Shil/IoTBasedSmartDustbin/assets/51587530/5b2b4828-94a6-4148-a984-e221143578e1)

* The lid opens in presence of object. There is a sensor that detects object and instract the servo motor to open the lid.

* There is another sensor that detects the garbage level and displays in a LCD display screen. The garbage level is also shown in the Blynk app.
* When the garbage level reaches 100% the display shows a message to empty the bin. There is a buzzar that will keep buzzing until the bin isnot empty. The servo motor will also remain off when the garbage level is full.
## Download Procedure

IDE used: Arduino uno.

Circuit Connection: Circuit connections are provided in the figure folder.

### Running the project code:

1. Download the blynkconnect.ino code and open in Arduino uno ide. Run the code in NodeMCU board and upload the code to nodeMCU.( Use own wifi setting and blynk setting)
2. Next download the garbagemanagement.ino code and open in Arduino uno ide. Select the Arduino board and upload the code in Arduino.

*** Keep the nodemcu and Arduino disconnected when uploading code 

A demo video is added in the repository



