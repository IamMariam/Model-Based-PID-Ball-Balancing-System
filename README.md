Project Overview

This project involves the design and implementation of a Model-Based PID Ball Balancing System using an Arduino board, a servo motor, an ultrasonic sensor, and a joystick module. The system continuously measures the position of a solid ball on a track using the ultrasonic sensor and returns the ball to a predetermined position using a PID controller. The PID controller is tuned manually using the joystick module to adjust the proportional (Kp), integral (Ki), and derivative (Kd) gains.

Hardware Components:

1- Arduino Board: The microcontroller used to implement the PID controller.

2- Servo Motor: Moves the track up and down to balance the ball.

3- Ultrasonic Sensor: Measures the ball's position on the track.

4- Joystick Module: Used to manually tune the PID controller gains (Kp, Ki, Kd).

5- Track and Flexible Holder: The track where the ball moves, and the flexible holder allows the track to tilt.

6- 3D Printed Parts: Some hardware components will be 3D printed and provided.

Software Components
1- Simulink: Used for model-based design and implementation of the PID controller.
2- Arduino IDE: For programming the Arduino board.
3- HyperTerminal: For serial communication to display the immediate distance of the ball on a PC.

Design Requirements:
- The system must be microcontroller-based using an Arduino board.
- The embedded software must be developed using Matlab Simulink.
- The system must measure the ball's position continuously and use a PID controller to balance the ball.


PID Controller Tuning
The PID controller is tuned using the joystick module:
  B1 Button: Controls the Kp gain.
  B2 Button: Controls the Ki gain.
  B4 Button: Controls the Kd gain.
  B3 Button: Enables or disables the tuning mode.

Joystick Stick: Increases or decreases the enabled gain by moving it up or down.
