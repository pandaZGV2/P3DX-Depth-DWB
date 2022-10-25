roscore

rosrun rosaria RosAria

roslaunch realsense2_camera rs_camera.launch align_depth:=true

roslaunch depthimage_to_laserscan launchfile_sample.launch

roslaunch turtlebot3_navigation turtlebot3_navigation.launch
