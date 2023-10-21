Create ROS2 workspace (mine is beebot_ws)
clone beebot_bringup and beebot_recognition into src directory
colcon build the whole workspace

starts the beebot recognition launch which runs the corrosion recognition node (ongoing the creation of the inference node)
ros2 launch beebot_bringup beebot_recognition.py 
the launch is already loading a config file
