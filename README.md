# RoboND-GoChaseIt
This aim of this project is to create a ball chaser robot in an previously created world(refer to build my world project). A camera and lidar sensor is attached to the rbot and it will continuously chase a white ball placed inside the world.

## Implementation

This is developed with gazebo workspace. 

## launch commands

For launching the world:

		cd /home/workspace/catkin_ws/
		source devel/setup.bash
		roslaunch my_robot world.launch
        
Launch  the following commands to develop the algorith for chasing:

		cd /home/workspace/catkin_ws/
		source devel/setup.bash
		roslaunch ball_chaser ball_chaser.launch

## rvis visualization

 'rvizconfig.rviz' file is used to visualize 
        
