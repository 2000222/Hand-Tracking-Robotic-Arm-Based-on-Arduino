#Intelligent Robotic Arm controlled with LeapMotion on Arduino Platform#

This is the node.js code for my robotic arm that's controlled by an Arduino and a Leap Motion device.  Libraries used are leapjs and johnny-five.  The code needs to be modified in the lengths of the robot arm parts (in terms of Leap Motion space).  Additionally, care must be taken to place the servo in such a way that the joints allow for a full range of motion.

Servos used:<br />
Base: HiTec HS-422<br />
Shoulder: HiTec HS-755HB<br />
Elbow: RadioShack "Standard Servo"<br />
End Effector: HiTec HS-81
