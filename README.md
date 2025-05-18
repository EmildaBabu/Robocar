# **ROBOTIC CAR CONTROLLE via UDP**
Robotic car uses the UDP protocol for fast and efficient wireless control. It allows real-time operation by receiving commands over a network with minimal latency.
## AIM
The aim of this project is to develop a robotic car that can be wirelessly controlled using the UDP protocol. UDP enables fast data transmission with minimal delay, making it suitable for real-time control applications. The robotic car will receive movement commands over a network without requiring a persistent connection.
## COMPONENTS
1. ESP32
2. Dual shaft motor - 2
3. Ultrasonic sensor
4. L293 module(DC motor control)
5. Buzzer
6. Robot chassis
7. Power supply Board
## BLOCK DIAGRAM
<img src="https://github.com/EmildaBabu/Robocar/blob/c759118c2dba742660804d15cc8b1e158f7b8add/projectblockdiagram.jpg?raw=true" alt="block diagram" width="300" height="200">
(Additionally, the ESP32 module is provided with the required power supply.)


## PROCEDURE
Step 1 : Connect the ESP32 microcontroller to the Arduino IDE through the appropritate communication port.

Step 2 : Connect a motor driver, such as the L293, to the digital pins of the ESP32 and the  alphabets to control the car's movement through UDP commands. 
        
        - 'a' for Forward
        - 'b' for Backward
        - 'c' for Left
        - 'd' for Right
        - 's' for Stop

Step 3 : Interface the ESP8266 with an ultrasonic sensor to measure the distance to obstacles in front of the car and Implement obstacle detection logic by setting a threshold distance (if distance comes >6), and automatically stop the car when an object is detected within that range. 

Step 4 : Upload the final code, send movement commands from a UDP terminal app, and test the car's response and automatic stop feature.


## OUTPUT[
<img src="https://github.com/EmildaBabu/Robocar/blob/abdf8944550e80e52a2ba0d17d013ba3f7e18c32/Working%20_model.jpg" alt="working model" width="400" height="250">
<img src="https://github.com/EmildaBabu/Robocar/blob/abdf8944550e80e52a2ba0d17d013ba3f7e18c32/controller.jpg" alt="working model" width="200" height="500">


