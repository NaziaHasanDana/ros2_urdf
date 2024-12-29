# ros2_urdf
URDF is an xml file format that includes elements (joints, links) of a robot. 
Installation:
# Step 1: Clone the repository
git clone git@github.com:NaziaHasanDana/ros2_urdf.git


# Step 2: Update the system packages
sudo apt update

# Step 3: Install Gazebo ROS packages
sudo apt install ros-humble-gazebo-ros-pkgs

# Step 4: Source the ROS 2 Humble setup script
source /opt/ros/humble/setup.bash

# Step 5: Navigate to the workspace directory
cd ~/ros2_urdf

# Step 6: Build the workspace
colcon build

# Step 7: Source the local workspace setup file
source install/setup.bash

# Step 8: Launch the URDF in Gazebo
ros2 launch my_robot_bringup my_robot_gazebo.launch.xml
