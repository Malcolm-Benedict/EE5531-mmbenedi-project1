# EE5531-mmbenedi-project1
### Written by: Malcolm Benedict
### Last updated: 1/14/2026
### Contact: mmbenedi@mtu.edu
A branch of the project which prints "Hello World" in poorly translated german.

This project aims to implement a simple ROS2 hello world node and a talker-listener package. The code is based on: https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html and https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html#writing-a-simple-publisher-and-subscriber-python and is written in C++ for ROS2 Jazzy.

To use this code, follow these steps:
1) place the folders in the /src folder of a properly initialized ROS workspace.
2) Then, run colcon build in the root of the workspace.
3) Source your terminal with source/install/setup.bash.
4) To run the code use ros2 run <package_name> <node_name> ex. $ ros2 run cpp_pubsub talker
