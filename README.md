# 4Servo-Arduino
This project demonstrates how to control 4 servo motors using Arduino Uno in Tinkercad

The motors first run using the Sweep example for 2 seconds, then all hold at 90 degrees

A walking motion algorithm for a humanoid robot is also proposed

# Components
    Arduino Uno
    4x Servo Motors
    Jumper Wires
    Tinkercad Circuits

# Wiring
    Servo 1 → Signal to Pin 3
    Servo 2 → Signal to Pin 5
    Servo 3 → Signal to Pin 6
    Servo 4 → Signal to Pin 9
    All VCC to 5V
    All GND to GND

# Code Behavior
    1. All servos sweep back and forth for 2 seconds
    2. All servos are set to hold at 90 degrees permanently

# Walking Motion Algorithm
    1. Start by setting all servos to a neutral position at 90 degrees
    2. Move the right leg forward by rotating the hip servo slightly forward
    3. Shift the robot’s weight to the right leg by tilting the torso slightly
    4. Move the left leg forward while keeping the right leg fixed
    5. Return the torso to the center position
    6. Move the left leg backward to the original position
    7. Shift weight to the left leg
    8. Move the right leg forward
    9. Repeat steps 3 to 8 in a loop for continuous walking

# Simulation

https://github.com/user-attachments/assets/ce4a44c5-86b6-4b52-b9e4-47e52e0088c6

