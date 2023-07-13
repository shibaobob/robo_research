# compile the workspace
catkin_make

# launch the RViZ and Gazebo
roslaunch panda_description description.launch

# run the python script
rosrun moveit_demo pushing_object.py
