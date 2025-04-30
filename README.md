# Pick-and-Place-Robot
An autonomous pick and place robot built using Arduino, servo motors, IR sensors, and Bluetooth control. Designed to automate repetitive or hazardous tasks, the robot detects, grips, and relocates objects with precision. Simulated in Proteus and wirelessly controlled via a custom Android app.

🤖 Pick and Place Robot
An autonomous mobile robotic arm designed to perform pick-and-place operations with precision and wireless control. This mechatronic system integrates servo motors, IR sensors, microcontrollers, and Bluetooth communication to automate repetitive or hazardous tasks in industrial environments.

📌 Features
Autonomous navigation using IR sensors and line-following logic
Multi-axis robotic arm controlled via servo motors for object manipulation
Bluetooth control with a custom Android app using HC-05 module
Microcontroller integration using AT89C2051 and AT80C52
Interrupt-based safety handling to prevent overextension of arm mechanisms
Simulation and circuit design using Proteus
Arduino-based control logic for motor movement and input processing

🛠️ Technologies Used
Arduino IDE
Proteus Simulation
HC-05 Bluetooth Module
AT89C2051 / AT80C52 Microcontrollers
Servo Motors, DC Motors
IR Sensors, Bump Sensors
C/C++ for embedded programming

🚀 How It Works
Robot navigates the environment using IR sensors and bump switches.
On detecting an object, the robotic arm is triggered to lower, grip, and lift.
The robot follows the path to the destination and places the object.
All operations can be manually overridden via Bluetooth app controls.

📦 Applications
Industrial part sorting and packaging
Handling hazardous materials (e.g., chemicals, sharp tools)
Educational and robotics research projects
Base model for future IoT or vision-enabled automation systems
