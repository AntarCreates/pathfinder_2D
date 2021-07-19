# pathfinder_description
This is a simulation project where I used my custom robot, Pathfinder for mapping and autonomous navigation using Robot Operating System (ROS)



Prequisites
* Any of the ROS1 distros properly installed on the dedicated ubuntu OS. You'll need to have a working catkin workspace set up for further progression. To learn more: http://wiki.ros.org/Documentation

#############################################--- Steps ---##########################################

step1: git clone the pathfinder_description package using the git clone command into the src folder of your catkin workspace.
git clone https://github.com/AntarCreates/pathfinder.git

step2: Update catkin enviornment using the following command in the catkin_ws directory
source devel/setup.bash # you'll need to run this command everytime you open a new terminal or make updates to your workspace

step3: Build the package using the following command
catkin_make

That's it! You made the package ready for further adventures.
