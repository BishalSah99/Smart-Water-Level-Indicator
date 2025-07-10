# Smart-Water-Level-Indicator
The Smart Water Level Indicator is an automatic system designed to monitor the water level inside a tank. It uses an ultrasonic sensor (HC-SR04) to measure the distance from the top of the tank (where the sensor is placed) to the surface of the water.

This distance helps the system understand how full or empty the tank is. Based on this, it gives alerts using LEDs or a buzzer, and optionally, displays the water level on an LCD screen.

🔍 How It Works – Step by Step
Ultrasonic Sensing:
The ultrasonic sensor sends a sound wave down to the water.
The wave hits the water surface and bounces back.
The time it takes to return is used to calculate the distance between the sensor and the water.

Arduino Processing:
The Arduino receives this distance.
It compares the distance with pre-set limits (e.g., 30 cm = empty, 5 cm = full).
It then decides which level the water is at: Low, Medium, or High.

Alert System:
If the water level is low, the red LED or buzzer turns on.
If it’s medium, the yellow LED turns on.
If the tank is full, the green LED turns on.

Optional Display:
An LCD display (if added) can show messages like:
"Water Level: 85%"
"Tank Full", "Tank Low", etc.

