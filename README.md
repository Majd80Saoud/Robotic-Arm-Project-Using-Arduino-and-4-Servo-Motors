# Robotic-Arm-Project-Using-Arduino-and-4-Servo-Motors

## Project Idea

This project aims to design and build a simple robotic arm that moves using four servo motors controlled by an Arduino board.
The robotic arm can perform basic movements such as:
 • Lifting and lowering the arm
 • Moving joints
 • Opening and closing the gripper (hand)

Each servo motor controls one joint, giving the arm a range of motion similar to a human arm but in a simplified form.

## Components Used
 1. Arduino Uno 
 2. 4 Servo Motors (SG90)
 3. Wires
 4. 6V Power Supply suitable for servos
 5. Robotic Arm Frame (3D printed)


  ##  How It Works
 • The code initializes all servos and defines their pins.
 • Then, it runs a sequence of movements that simulate human-like arm motion:
 1. Set the arm to the initial position.
 2. Gradually move each joint using for loops to control the servo angle.
 3. Open and close the gripper to simulate grabbing an object.
 4. Return the arm to the starting position.

Delays are added between movements (delay()) to make the motion smooth and visible.


## Code Logic
 • Each movement is based on servo rotation angles from 0° to 180°.
 • for loops are used for smooth, step-by-step movement instead of sudden changes.
 • Each servo corresponds to a specific joint, allowing coordinated motion between all parts of the arm.
