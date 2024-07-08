# Tutorials

1. Introduction to ROS2: https://github.com/vicoslab/dis_tutorial1
## Homework 1: 
+ Create a new package. You can use C++ or Python.
+ In the package create a publisher node that periodically sends a custom message. The custom message should have a string field, an integer field, and a bool field.
+ Create a subscriber that receives the message and prints out its contents.
+ In the new package you created, write a service node that accepts an array of integers and returns its sum. 
+ Demonstrate its correctness by writing a client that generates random sequences of 10 integers and prints out the sequence and the result returned from the service.

2. Introduction to ROS2 - some additional concepts : https://github.com/vicoslab/dis_tutorial2

## Homework 2
Your task is to create a service node which moves the simulated turtle from the turtlesim package. Check the custom msgs and srvs documentation for help.

The service request should contain a string and an integer field. The string should be one of:

+ "circle"
+ "rectangle"
+ "triangle"
+ "random"
and the integer field specifies the duration in seconds.

The node should then move the turtle in the specified trajectory for the given duration in the integer field. After the given duration the turtle should stop moving. The response to the client should contain a string field with the previous issued movement type.

Upload your code in a single .zip file (compress the package(s))


3. The Turtlebot 4 https://github.com/vicoslab/dis_tutorial3
4. Some further information and help: https://github.com/vicoslab/dis_tutorial4
5. The Real Turtlebot 4 https://github.com/vicoslab/dis_tutorial5
6. Point Cloud Library and ring detection: https://github.com/vicoslab/dis_tutorial6
7. Adding a robot arm and a camera to the Turtlebot4: https://github.com/vicoslab/dis_tutorial7
