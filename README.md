# Mini Project – Mobile Robot Obstacle Avoidance with ROS 2 🤖

A simple AI-powered mobile robot project that uses **ROS 2** to navigate and avoid obstacles autonomously.

## 🚀 Project Highlights
- Developed using **ROS 2 (Humble)** and Python.
- Uses AI and sensor data for **simulated** obstacle avoidance in Gazebo.
- Robot model designed using **URDF (Unified Robot Description Format)**.
## 🛠️ Setup Instructions

### 1. Install ROS 2 Humble
```bash
sudo apt install ros-humble-desktop
source /opt/ros/humble/setup.bash
ros2 pkg create --build-type ament_python --license Apache-2.0 <package_name>
colcon build --packages-select my_package
source install/local_setup.bash
