This is C code written for Arduino board for a line following robot.
It uses PID algorithm to correct errors and thereby controlling the motors.
My version of PID here divides the 8 IR sensor arrays into left and right parts
and the left part sensors control the right motor and vice-versa.
A working demo is provided in the video titled 'gqah'. 
Moreover the bot goes around any obstacle that come in its path. It detects
obstacle by HC-SR04 sensor and follows a routine when it encounters
an obstacle.
