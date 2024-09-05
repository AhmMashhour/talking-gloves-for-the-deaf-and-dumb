# Talking Gloves For The Deaf & Dumb

This project involves the development of a glove-based gesture recognition system using flex sensors and an Arduino microcontroller. The system captures hand gestures and translates them into corresponding characters, which are then sent via a serial connection. It includes calibration for sensor adaptability, reading and mapping sensor values to angles, and recognizing specific gestures for different characters.

## Features
- Uses flex sensors to detect finger bends.
- Calibrates sensors for adaptive accuracy.
- Maps sensor readings to angles.
- Recognizes and outputs corresponding characters for specific gestures.

## Components
- Arduino Nano
- Flex Sensor (Bend Sensor)
- Biaxial Analog Accelerometer Module (ADXL 335)
- HC-05 Bluetooth Module

## Usage
- Wear the glove with the sensors connected.
- Power the Arduino Nano.
- Perform hand gestures.
- Observe the corresponding characters sent to the serial monitor.

## Code Overview
The code is divided into several sections:

- Initialization: Sets up the serial communication and initializes sensor variables.
- Calibration: Calibrates the sensors for 15 seconds after startup.
- Main Loop: Continuously reads sensor values, maps them to angles, and checks for specific gestures to output the corresponding characters.

## Contributing
- Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

### License
- This project is licensed under the MIT License.
