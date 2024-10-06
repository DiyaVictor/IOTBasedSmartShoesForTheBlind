Obstacle Detection System using IR Sensor, LED, and Buzzer

![ezgif-7-aca07e6e07](https://github.com/user-attachments/assets/36915d6d-9c35-4c45-8525-66432f8ea9e0)
![Screenshot 2024-10-06 125834](https://github.com/user-attachments/assets/fcf4eeed-4dd6-4a9d-b221-b2b34354d3dd)
![ezgif-7-537916eb93](https://github.com/user-attachments/assets/98a003dc-887b-45f4-a7d9-58cba259a2f1)

This Arduino-based project detects obstacles using an IR sensor and responds by lighting up an LED and sounding a buzzer. The system is simple yet effective for applications like proximity detection or alert systems. Below is a breakdown of the setup:

Components:
Arduino UNO (or compatible)
IR Sensor: Detects the presence of an obstacle.
LED: Lights up when an obstacle is detected.
Buzzer: Sounds an alert when an obstacle is detected.
Resistors: For current limiting in the LED.
Jumper Wires: For connecting components.
Code Functionality:
The IR sensor constantly monitors for obstacles.
If an obstacle is detected (detect == HIGH):
The LED turns on.
The buzzer sounds at a frequency defined by the sound variable (250 Hz).
If no obstacle is detected (detect == LOW):
The LED and buzzer turn off.
The system operates with a small delay of 300ms between each check to avoid rapid switching.
How to Use:
Connect the IR sensor, LED, and buzzer to the Arduino as per the pin definitions in the code.
Upload the provided sketch to the Arduino board.
Observe the LED lighting up and the buzzer sounding when an object comes within range of the IR sensor.
Pin Configuration:
LED: Connected to digital pin 4.
Buzzer: Connected to digital pin 5.
IR Sensor: Connected to digital pin 6.
