## Canopybot 


## The repository contains the following ros packages: 

 - canopybot_model : Contains URDF model, Meshes, World files and launch files to spawn the robot in Gazebo.
 - canopybot_navigation : Contains code for implementing navigation of the robot. 
 - canopybot_vision : Contains code for scene understanding, semantics, etc.
 - canopybot_hardware : Contains code that interfaces to the real robot.
 

## Setup

```
$ cd ~/catkin_ws/src 
$ git clone repo
$ cd ..
$ vcs import src < src/canopybot/dependencies.repos
$ catkin_build
$ source devel/setup.bash
```

 @author : Utkarsh Bajpai, 2022
