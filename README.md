# compile the workspace
catkin_make

# source
source ./devel/setup.bash

# launch the RViZ and Gazebo
roslaunch panda_description description.launch

# run the python script
rosrun moveit_demo pushing_object.py
