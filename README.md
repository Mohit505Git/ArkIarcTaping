# Ark IARC Taping
## Introduction
-Involves ROS kinetic (to subscribe positions and publish positon setpoints)

-Gazebo Simulator

-Desmos Graph plotter (https://www.desmos.com/calculator to view the profile of the taping trajectory)

-C++ (Language used)

This project involves the mathemetical model of trajectories to be followed by a multirotor sytem to tap a ground robot (Subject to IARC Mission 7)
provided the location of the later and former in with respect to the arena. The localisation is performed by vision and is publish to topic thus incoorporating ROS
. Unlike previous model this model focuses on the dynamic nature of the ground bot. Thus state of the multirotor is constantly updated with the postion of the ground bot with respect to the position of former.


 
