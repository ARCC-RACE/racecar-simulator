Racecar Simulator
=================
Simulates an RC car in the MIT tunnel.
1. Install system dependencies
 - sudo apt-get install ros-kinetic-gazebo-ros-control
 - sudo apt-get install ros-kinetic-ros-control
 - sudo apt-get install ros-kinetic-ackermann-msgs
 - sudo apt-get install ros-kinetic-joint-state-controller
 - sudo apt-get install ros-kinetic-effort-controllers
2. Run `roslaunch racecar_gazebo racecar.launch` or `roslaunch racecar_gazebo racecar_tunnel.launch`
3. `rosrun racecar_control keyboard_teleop.py`
