# Security-Door-Stimulation
A stimulation project of a security system that requires the password from user to open the door

# Password Protected Door Lock Simulation

This project is an Arduino-based simulation of a password-protected door lock system. The system uses an Arduino Uno to control a keypad, servo motor, buzzer, and LED indicators. A user enters a password through the keypad, and the Arduino checks whether the entered password is correct.

If the password is correct, the green LED turns on, the buzzer gives a confirmation sound, and the servo motor rotates to simulate the door opening. If the password is incorrect, the red LED turns on and the buzzer produces an error sound to indicate failed access.

## Components Used

- Arduino Uno
- 4x4 Keypad
- Servo Motor
- Buzzer
- Red and Green LED indicators
- Jumper wires
- Breadboard / circuit simulation software

## How It Works

1. The user enters a password using the keypad.
2. The Arduino reads the keypad input.
3. The entered password is compared with the stored correct password.
4. If the password is correct:
   - The green LED turns on.
   - The buzzer gives a success signal.
   - The servo motor rotates to open the door.
5. If the password is incorrect:
   - The red LED turns on.
   - The buzzer gives an error signal.
   - The door remains closed.

## Project Purpose

The purpose of this project is to demonstrate a simple electronic security door system using Arduino. It shows how input devices, output indicators, and motor control can work together in an access-control system.

