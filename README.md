# gazebo_teleop_movement
the contents are only the src folder.
these need to be in the catkin_ws.
after adding them to your src you need to launch the world in gazebo and in the other terminal type the command 
rosrun turtlesim turtle_teleop_key /turtle1/cmd_vel:=/mybot/cmd_vel
to start controlling using the keyboard.
