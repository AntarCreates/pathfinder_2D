## Hope you got the package set up without any error. Now let's move forward.
We will start by moving the robot.
The robot, pathfinder has four wheels, a 2D Lidar set up on top and a Kinect camera set up at the front.
The robot moves using the skid steer drive mechanism, which means the robot moves depending on the relative velocity of the four wheels.

Very simply speaking, when two wheels of one side of the robot move slowly or do not move at all, 
the robot will rotate towards that direction as the other side will push it that way. Now with that information, let's drive it around.

In this case, we will use the teleop_twist_keyboard node from the teleop_twist_keyboard package, which will allow us to control the robot on gazebo using our keyboards.

**Step1:Run the following command, if you do not have the package installed
sudo apt-get install ros-{your ros distro name}-teleop-twist-keyboard**

**Step2: Open a terminal in the catkin workspace and bash the source using the following command:
source devel/setup.bash**

**Step3: Launch the robot in Gazebo using the following command in a terminal. gazebo is a simulator, that should come preinstalled if you installed the full version of your ROS distro.
roslaunch pathfinder_description gazebo.launch**

This should launch the robot in gazebo in an empty environment. Insert objects from the insert tab according to your own preference to set up a world. Be creative.

**Step4: In another terminal, run the command as below:
rosrun teleop_twist_keyboard teleop_twist_keyboard.py**

This should bring up the control keys in the terminal. Press " i " to make the robot keep moving forward, "," to move backwards, " j " for left, " l " for right and " k " for stop. 
More control keys should be given in the same terminal with proper description. 

#### Note: If you find that the file is not found yet it is in your folder, it is most likely because you didn't use the "source devel/setup.bash" command when opening a new terminal.

**Step5: Now while the teleop_twist_keyboard terminal is selected, move the robot around with designated keys.**

**Close all windows using ctrl+C**

## Had a good time? Let me know! ##



