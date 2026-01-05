# Animatronic-Head
A basic animatronic head that looks at a any person it sees through the camera.

<img src="https://github.com/user-attachments/assets/ebe5c8b9-d99e-4b47-80f2-551ed321744c" width="300">

<h2>Introduction</h2>
  This project was initially created as part of my Physics Project where we were given the freedom to experiment with new ideas. The project is based on the ESP32 Cam module which allowed us to have the build in camera module with no extra hassle. The camera feed scanned for people which would be outputted as servo code to move the eyes and the head to look in the direction of the person. If no person was detected, then the head would present with an idle animation which was animated to look like it was reading a book.


## Electronics
We used the following to make our project-
 - ESP32 ESP-WROOM-32 0.96" OLED WiFi Bluetooth Dual Core Module
 - 16-Channel 12-bit PWM Servo Motor Driver I2C Module
 - SG90 Servo Motors x 4
 - Voltage Regulator

## Mechanics
For this project, since we did not have access to any 3D printer, we needed to use cardboard and some "jugaad" to form the mechanical aspects of the project.

Some 3D renders have been given below (I was not too comfortable with CAD at the time so I had used Blender to get an idea of what we had to do)

<div align = "center">
<img src="https://github.com/user-attachments/assets/5471cee3-4c53-4de5-8f60-724635195bc9" width="500"><br>
Head - Left/Right Mechanism
<br><br><br>

<img src="https://github.com/user-attachments/assets/6eaab656-f2f9-4f27-8ae6-bbb705383a58" width="500"><br>
Head - Up/Down Mechanism 
<br><br><br>

<img src="https://github.com/user-attachments/assets/6eaab656-f2f9-4f27-8ae6-bbb705383a58" width="500"><br>
Eyes - Left/Right Mechanism

</div>


