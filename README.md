# ATMR-All-Terrain-Mini-Rover
Project Created By -
Aahan M
ATMR (All Terrain Mini Rover), 2025


This ATMR is designed and accesorized such that it is capable of doing many things and controlled via a custom Android app over Wi-Fi using an ESP32 microcontroller.
The car features movement control, headlights, and a horn — all accessible through a simple mobile interface.

# Features -
Controls via Android App (Wi-Fi)
->     Forward, Backward, Left, Right, Stop functions
->     Headlight on / off toggle
->     Horn (buzzer)push button
->     Editable IP address column in the app


# Hardware Used -
ESP32 Development Board
L298D Motor Driver
12 to 24 volts opperational DC Motors (x2)
Cast Acrylic sheet (un-cut)
Laser Machine
Buzzer (for horn)
LED (for headlight)
Power Supply (Li-ion battery or similar)

# Android App -
The Android app connects to the ESP32 over Wi-Fi and allows full control of the RC car.

# App Controls -
Arrow Buttons: Forward, Backward, Left, Right
Stop: Stops all motion
Horn: Momentary buzzer sound
Light: Toggle headlight on/off
IP Address: Editable field to connect to your ESP32 IP

# How It Works -
The ESP32 hosts a web server or listens on a fixed IP address.
The app sends HTTP GET requests to control the car.
The ESP32 reads the request and controls the motors, lights, or buzzer using GPIO pins.

# Getting Started -
1. Flash the ESP32 with Arduino code that listens for HTTP requests and controls the components.
2. Connect the ESP32 to a Wi-Fi network.
3. Install the provided Android APK on your phone.
4. Launch the app, enter the ESP32 IP address, and start driving.

# Future Improvements - 
1. Add live camera feed using ESP32-CAM
2. Enable speed control with PWM
3. Monitor battery level in the app
4. Integrate voice control features

