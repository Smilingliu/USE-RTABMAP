# USE-RTABMAP
An example of the use of the rtabmap package, the keyboard controls the robot to walk around the environment and reconstruct a map of the environment. 

The robot's sensor includes a hokuyo radar and a kinect camera. This program needs to run in the ros workspace, this program includes 3 packages: 

The ROBOT package includes robot settings and environment settings.

The RTABMAP package includes map settings, rviz settings, and more. 

The teleop_twist_keyboard package is the keyboard control for the robot.

First install the RTAB-MAP package.

Then you need to enter the following command on the terminal:

Roslaunch ROBOT world.launch

Rosrun teleop_twist_keyboard teleop_twist_keyboard.py

Roslaunch RTABMAP mapping.launch

rtabmap-databaseViewer ~/.ros/rtabmap.db

![picture](https://github.com/Smilingliu/USE-RTABMAP/blob/master/picture.png)
