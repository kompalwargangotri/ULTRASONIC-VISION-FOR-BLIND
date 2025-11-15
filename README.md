# ULTRASONIC-VISION-FOR-BLIND
An Arduino-based ultrasonic vision system designed to assist blind individuals by detecting nearby obstacles and providing real-time audio or vibration alerts. The project enhances user safety by identifying objects, stairs, pits, and other potential hazards using ultrasonic sensing.

Steps to Build the Ultrasonic Vision System

1. Gather Required Components
   
•	Arduino Uno

•	Ultrasonic Sensor HC-SR04

•	Buzzer

•	Blind Stick

•	9V Battery

2. Pin Connections and Configuration
   
(1) VCC and GND Connections

•	Connect the VCC pin of both HC-SR04 sensors to the 5V pin of the Arduino Uno.

•	Connect the GND pin of both sensors to the GND pin of the Arduino Uno.

(2) Trigger and Echo Pins

Each HC-SR04 sensor requires two digital pins:

Sensor 1 (Front-Facing):

•	TRIG → Digital Pin 2

•	ECHO → Digital Pin 3

Sensor 2 (Downward-Facing):

•	TRIG → Digital Pin 4

•	ECHO → Digital Pin 5

(Pins can be changed as long as TRIG–ECHO pairs are correct.)

(3) Buzzer Connection

•	Positive terminal (+) → Digital Pin 6

•	Negative terminal (–) → Arduino GND

3. Upload the Arduino Program
   
Upload the code that:

•	Measures distance and depth using ultrasonic sensors

•	Activates the buzzer when obstacles or pits are detected

4. Hardware Assembly
   
•	Mount all components on the blind stick securely.

•	Place the downward-facing sensor approximately 10 cm above the base to detect stairs or pits.

•	Mount the front-facing sensor to detect objects ahead.

•	Ensure wiring is taped/fixed properly for safety.

5. Testing and Calibration
    
•	Verify all wiring connections.

•	Test the prototype on real obstacles, stairs, and depth variations.

•	Adjust program parameters such as:

o	Distance threshold

o	Depth detection range

o	Buzzer alert sensitivity

Adjust according to the user's needs and environment.

