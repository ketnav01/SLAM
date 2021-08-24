# SLAM
# SLAM (Mapping and Localization) using Turtlebot

Run roslaunch turtlebot3_gazebo turtlebot3_world.launch on a terminal

On another terminal run roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml on Rviz

In another terminal run:rosrun udm_group2_gb global_localization.py

Call the service with:rosservice call /global_localization_Service "a: data: '100'"
