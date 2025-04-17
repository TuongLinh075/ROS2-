# Install ROS
sudo apt install ros-humble-desktop
# Environment setup
source /opt/ros/humble/setup.bash
# Create packages
ros2 pkg create --build-type ament_python --license Apache-2.0 <package_name>
# build packages  
colcon build --packages-select my_package
# source
source install/local_setup.bash
