# aruco_nav_gazebo


# dependencies
http://wiki.ros.org/hector_quadrotor

http://wiki.ros.org/fiducials

To start 
*roslaunch aruco_nav aruco_nav.launch*


To teleop quadrotor

*rosservice call enable_motors true*

*rosrun teleop_twist_keyboard teleop_twist_keyboard.py cmd_vel:=cmd_vel*


To print pose estimation 

*rostopic echo /fiducial_pose *
