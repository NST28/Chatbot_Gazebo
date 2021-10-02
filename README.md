# Chatbot_Gazebo

cd ~/Chatbot_Gazebo /n
catkin_make /n
source devel/setup.bash
roslaunch ur5_notebook start.launch
rosrun retract_table2org.py
rosrun card_handle.py
