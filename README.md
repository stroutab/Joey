# Joey

This directory contains information for the JoeBotics-7547) robot.

This robot was made for the 2013-14 FTC game: Block Party.

Robot description:  The robot is two wheel (with encoders).  It has three additional motors: a flag spinner, a winch and arm (with encodrer).  There are two flippers on the arm for grabbing blocks and an additional servo on top for programmers training.  The robot has an optical distance sensor, a gyro, a light sensor and a IR sensor.  The robot uses legacy equiptment with the new Android phones.

Configuration file: 		Joey

	Motor Controller 1:		1: leftWheel		Reverse, Encoder
							2: rightWheel		Forward, Encoder

	Motor Controller 2:		1: arm				Forward
							2: flagSpinner		Forward

	Motor Controller 3:		1: winch			Reverse

	Servo Controller 1:		1: leftFlipper		Forward, (0 - 0.5)
							2: rightFLipper		Reverse, (0 - 0.5)
							3: flag

	Sensors:				1:Distance
							Gyro
							Light
							IR

Controls:

	Left-Joystick	Left Wheel
	Right-Joystick	Right Wheel
	A				Flag Spinner Foward
	B				Flag Spinner Backward
	X				Winch In
	Y				Winch Out
	Right-Trigger	Arm Up
	Left-Trigger	Arm Dowm
	Right-Bumper	Toggle Flippers (Open <-> Closed)
	Left-Bumper		Toggle Driving  (Arm Forward <-> Flag Forward)
	D-Pad			Slow (Forward, Left, Right, Backward)


