# 4WD_description
ROS Autonomy Simulation

#Cloning 4WD_description to /catkin_ws/src folder

cd ~/catkin_ws/src

git clone https://github.com/SinLoops333/4WD_description.git
cd ~/catkin_ws 
catkin build 
source ./devel/setup.bash 
source ~/.bashrc 

Launch Rviz and Gazebo

roslaunch 4WD_description gazebo.launch  

