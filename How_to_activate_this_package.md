
# This is a simulation project where I used my custom robot, Pathfinder for mapping and autonomous navigation using Robot Operating System (ROS). The first repository will deal with 2D mapping and second one (to be added) will look into 3D mapping and navigation. #



## Prerequisites ##
* Any of the ROS1 distros properly installed on the dedicated ubuntu OS. You'll need to have a working catkin workspace set up for further progression. To learn more: http://wiki.ros.org/Documentation

#############################################--- Steps ---##########################################

step#1: git clone the pathfinder_description package using the git clone command into the src folder of your catkin workspace.

`git clone https://github.com/AntarCreates/pathfinder.git `

## _Note: The package in your src folder must be named as "pathfinder_description", otherwise, the commands given in the other instructive files will not work. You can change it if you want, but then you have to chanage the name in almost every single file. Make sure the folder is saved in your src folder as "pathfinder_description"_ * ##

step#2: Update catkin enviornment using the following command in the catkin_ws directory
source devel/setup.bash # you'll need to run this command everytime you open a new terminal or make updates to your workspace

step#3: Build the package using the following command:

`catkin_make`

Step#3: Check whether or not everything is okay by spawing the robot in gazebo using the following command:

`roslaunch pathfinder_description gazebo.launch`


# Annnnnd....That's it! You made the package ready for further adventures! #
