# Graph SLAM
## Project Overview
This project contains an implemention for graph SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world. In which, there is a combination of information about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot over time. SLAM gives a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world.

| ![robot_world.png](images/robot_world.png) | 
|:--:| 
| **Example of SLAM output (estimated final robot pose and landmark locations)** |
