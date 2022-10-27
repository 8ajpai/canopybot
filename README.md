## Canopybot 
Code for the project "Development of a small agricultural robot for under canopy inspection of Maize Plants". 

## Requirements
- Ubuntu 20.10
- ROS Noetic

## Docker Setup
TO:DO

## Repository Architecture: 

 - canopybot_model : Contains URDF model, Meshes, World files and launch files to spawn the robot in Gazebo.
 - canopybot_navigation : Contains code for implementing navigation of the robot. 
 - canopybot_vision : Contains code for scene understanding, semantics, etc.
 - canopybot_hardware : Contains code that interfaces to the real robot.
 

## Simulation Setup

```
$ cd ~/catkin_ws/src 
$ git clone repo
$ cd ..
$ vcs import src < src/canopybot/dependencies.repos
$ catkin_build
$ source devel/setup.bash
```

## Extra Steps for Hardware Setup

After completing the "Simulation Setup", do the following:

```
$ sudo apt-get install libpcap-dev
$ ~/catkin_ws
$ vcs import src < src/canopybot/canopybot_hardware/dependencies.repos
$ catkin_build
$ source devel/setup.bash
```

 @author : Utkarsh Bajpai, Univerity of Bonn, 2022 
