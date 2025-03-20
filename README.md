#Automated Factory - Microcontroller Project
Overview
The Automated Factory is a smart sorting system that integrates computer vision and weight sensors to classify and differentiate products in real-time. By automating the product sorting process, the system enhances efficiency, accuracy, and productivity in factory operations while reducing manual labor and errors.

How It Works:
Object Detection: A camera captures images of moving objects on a ramp.
Data Processing: The image is sent via WiFi to the backend for analysis.
Weight Measurement: A load cell measures the object's weight.
Sorting: The system classifies the object based on its characteristics (image + weight).
Real-Time Display: The LCD display shows object type, count, and weight.

Key Components:
Arduino UNO
ESP-32 CAM (for image capture & transmission)
ATmega32 (microcontroller for control operations)
HX711 & Load Cell (for weight measurement)
LCD Display (for real-time updates)

Motivation:
Traditional factories rely on manual sorting, which is prone to errors, inefficiency, and high labor costs. Our system automates this process with computer vision and IoT-based weight sensing, making inventory management seamless and more efficient.

Contributors:
Ahmmad Nur Swapnil (2005009)
Al Muhit Muhtadi (2005013)
Ekramul Haque Amin (2005022)
