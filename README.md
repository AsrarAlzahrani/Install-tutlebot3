# Install tutlebot3

Install turtulebot3 package : Open the folder (ROS workspace) and install the dependent packages 
use this commands "cd ~/Documents/wallE_ws/src/" , "git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git",  "git clone https://github.com/ROBOTIS-GIT/turtlebot3.git" and "cd ~//Documents/wallE_wss && catkin_make"

 Open the bashrc file by add this "gedit ~/.bashrc" and detect the model by this line add the bottom of the file "export TURTLEBOT3_MODEL=burger" then use this line for You don't have to sign out and sign in again "source ~/.bashrc"
 
 Install turtulebot3_simulation package :
 Open the folder (ROS workspace) and install the simulation package use this command "git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git"
 
TurtleBot3 simulation Using RViz:  
use this command for Launch the simulation robot "roslaunch turtlebot3_fake turtlebot3_fake.launch" and move TurtleBot3 around the screen by this line "roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch"
