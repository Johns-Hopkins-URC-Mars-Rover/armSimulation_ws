# armSimulation_ws
ROS workspace for simulating the arm autonomously typing on the keyboard

### To use packages in this repository:
1. Make sure you have ROS2 Humble installed.
2. Clone this repository into your home directory.
3. In the root of the workspace, run `colcon build`.
4. Open a new terminal, navigate to this workspace, and run `source install/setup.bash`

### cmake_arm_urdf:
To view the arm in Rviz with sliders to control the joints, run `ros2 launch display.launch.py`.\
To view the arm in Gazebo, run `ros2 launch gazebo_launch.py`.
