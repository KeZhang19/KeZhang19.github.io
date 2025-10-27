---
permalink: /
title: "Research direction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

 I am currently working in the field of dexterous hand grasping, and I have previously been involved in perception and planning for traditional robot navigation.
 
 Please refer to my [CV](https://github.com/KeZhang19/KeZhang19.github.io/blob/master/assets/%E7%AE%80%E5%8E%86.pdf)

Project
======
Quadruped Robot Navigation
------
Implementing localization and navigation for quadruped robots in indoor environments​​
- Localization and mapping algorithm based on FastLIO
- ICP global relocalization functionality
- A* global planning with TEB local planning
- Integrated Scan Context loop closure detection
- Map beautification using image processing techniques
- MPC trajectory tracking control

Quadruped Robot Simulation Platform
------
Building quadruped robot models in Gazebo with ROS2 integration for simulation testing​​
- Quadruped robot simulation setup
- Testing various VLM model performances
- Vilt model inference acceleration
- ROS2 integration with multiple sensor inputs
- Deployment of FastLIO, ICP, A*, FarPlanner, and Vilt algorithms in simulation

Self-Balancing Bicycle Project
------
​Using RT1064 as main controller with brushless motor drive for path following and special tasks
- Attitude estimation using gyroscope data with cascade PID for self-balancing
- FOC algorithm for motor control
- Accept GPS signals for path planning and task execution

Baidu EdgeBoard Smart Car
------
Use the edgeboard as the master and achieve specific tasks on the defined track
- Algorithm development on Baidu EdgeBoard processor for path following and special element tasks
- Serial communication with TC264 for vehicle motion control
- Multi-threaded framework design in Linux environment
- V4L2 camera reading, AI inference deployment
- Path generation and normalization, fuzzy PID algorithm deployment

https://github.com/KeZhang19/KeZhang19.github.io/blob/master/images/4.mp4

3rd gen i5 as main controller, Arduino for Ackermann chassis control​​
------
- AMCL-based localization 
- A* algorithm for global path planning with global map 
- TEB algorithm for local dynamic obstacle avoidance with local map
- Fuzzy PID control for local path trajectory tracking
