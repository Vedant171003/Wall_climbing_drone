# Wall_climbing_drone
Wall Climbing Drone ROS Package
This ROS2 package contains the necessary files to simulate a wall climbing drone in Gazebo. The package includes a URDF description of the drone, along with launch files to launch the Gazebo simulation environment.

Package Contents
urdf/: Contains the URDF description files for the wall climbing drone.
launch/: Contains launch files to launch the Gazebo simulation environment.
config/: Contains configuration files for the drone controllers and sensors.
Dependencies
This package has the following dependencies:

ROS2 (Robot Operating System): This package has been developed and tested with ROS Humble.
Gazebo: The Gazebo simulator is used to simulate the drone and its environment.
Installation
To use this package, clone the repository into your ROS workspace (e.g., catkin_ws/src):

bash
Copy code
cd ros_ws/src
git clone https://github.com/yourusername/wall_climbing_drone.git
Then, build your ROS workspace:

bash
Copy code
cd ros_ws
colcon build
Usage
Launch the Gazebo simulation environment with the following command:

bash
Copy code
roslaunch wall_climbing_drone gazebo.launch
This will launch Gazebo with the wall climbing drone model.

Additional Information
For more information on the drone model, simulation parameters, or how to use the package, refer to the documentation or contact the package maintainer.
