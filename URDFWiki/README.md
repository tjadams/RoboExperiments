https://docs.ros.org/en/iron/Tutorials/Intermediate/URDF/Building-a-Visual-Robot-Model-with-URDF-from-Scratch.html

# Usage instructions
1. Copy-paste HelloWorld.urdf into `~/ros2_ws/src/urdf_tutorial/`
2. Open new terminal
3. Setup global ROS 2 source: `source /opt/ros/iron/setup.bash`
4. Setup ROS 2 workspace source: `source ~/ros2_ws/src/install/setup.bash`
5. `cd ~/ros2_ws/src`
6. Rebuild with new urdf file: `colcon build`
7. Launch a visualization of the URDF: `ros2 launch urdf_tutorial display.launch.py model:=urdf/HelloWorld.urdf`
