# BluetoothControlledRobot
Robot controlled by an android application through an inbuilt Bluetooth module.

The android application controlled robot communicates via bluetooth to the bluetooth module present on the robot. While pressing each button on the application, 
corresponding commands are sent via bluetooth to the robot.

The commands are sent are in the form of ASCII. The arduino on the robot then checks the command received with it’s previously defined commands
and controls the servo motors depending on the command received to cause it to move forward, backward, left, right or to stop. This allows to create
an android controlled robot
