# Automated-Toll-Collection-System
Designed using RFID Module and Arduino.

## Introduction
This project is a demo of a **Smart Toll Tax Collection System**. Consider there are n numbers of vehicles at Toll Plaza. When these vehicles cross the **IR Sensor**, the gate will be closed. At the same time, the **LCD** will display to put the Card to the reader for scanning. Then you can put your card on **RFID** and pay your bill. When the bill is successfully paid, then you can go towards the 2nd Gate. When a vehicle crosses the 2nd IR Sensor, the gate will be opened and you can go. In case the card doesn’t have a balance, you can **recharge** the card using this RFID and **Keypad** by entering the amount.

## Flow Chart
<p align="center" width="100%">
<img src = "https://github.com/Fangzzxx/Automated-Toll-Collection-System/blob/main/Flow%20Chart.jpg" width = "40%" height = "40%" />
</p>

The RFID reader checks for valid, invalid, or low balances. If invalid and low balance the LCD Screen will show insufficient balance. The RFID Card can be loaded to balance using the Keypad System. When the Card is recharged, the user becomes eligible for paying and going through the toll gate.

The toll gate is fitted to the Servo Motor where the spindle of the motor rotates in a fixed angle step. When the user swipes the card the reader sends the signal to the controller and the controller checks for a valid user. If the card is valid then the controller sends a signal to the Servo motor to rotate in an anticlockwise direction so the gate opens. Some delay function is added so that the gate remains open until the vehicle moves after some time delay the controller passes the signal to rotate the Servo motor in a clockwise direction to close the gate.

## Circuit Diagram
<p align="center" width="100%">
<img src = "https://github.com/Fangzzxx/Automated-Toll-Collection-System/blob/main/Circuit%20Pin%20Diagram.jpg" width = "40%" height = "40%" />
</p>


[Working Video](https://github.com/Fangzzxx/Automated-Toll-Collection-System/blob/main/Exploratory%20Project.mp4)


 

