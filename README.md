# TouchID Arduino Security System

## Description
An Adafruit fingerprint sensor module(R307S) to unlock a security system. When a valid fingerprint is detected, it activates(HIGH) a relay pin for a predefined duration to unlock the system.

## Hardware Requirements
- Adafruit fingerprint sensor module (R307S)
- Arduino UNO board
- 5V Relay module (connected to pin 13)
- LM2596 DC-DC Buck Converter

## Environment
- Arduino IDE

## Installation
1. Connect the Adafruit fingerprint sensor module to the Arduino board according to the provided pin configuration.
2. Open the `main.ino` file in the Arduino IDE.
3. Upload the sketch to your Arduino board.
4. Open the Serial Monitor to view the output.

## Usage
1. Ensure that the Adafruit fingerprint sensor module is properly connected to your Arduino board.
2. Upload the sketch to your Arduino board.
3. Open the Serial Monitor to view the output.
4. The system will wait for a valid fingerprint. Once detected, it will activate the relay pin to unlock the system for a predefined duration.
   
## Fingerprint Module(R307S)

The Adafruit Fingerprint Sensor Library is designed to work with Adafruit's fingerprint sensors, providing an easy-to-use interface for fingerprint enrollment and recognition functionalities. This library simplifies the process of integrating fingerprint sensors into Arduino projects, allowing users to easily enroll and delete fingerprints, as well as perform fingerprint matching and identification.

## Enrolling Fingerprint
- Connect the Adafruit fingerprint sensor module(R307S) to the Arduino board according to the provided pin configuration.
- Open the `adafruit-sensor-lib/enroll.ino` file in the Arduino IDE.
- Upload the sketch to your Arduino board.
- Open the Serial Monitor it will ask for you to type in the ID to enroll - use the box up top to type in a number and click Send.
- Then go through the enrollment process as indicated. When it has successfully enrolled a finger, it will print Stored!
  
## Additional Notes
- Ensure that the baud rate and other configurations in the sketch match your hardware setup.
- Please refer to the Adafruit Fingerprint sensor documentation for detailed information on hardware connections and usage.

## Issues 

[Submit Issues](https://github.com/riz4d/TouchID-ArduinoSecurity/issues)

