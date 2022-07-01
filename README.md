# Tufts_Create3_Examples

Welcome! In this repo we (some undergrad mechanical engineering students at Tufts University) aim to help you master the iRobot® Create® 3 Educational Robot through code examples and design challenges. To control the Create® 3 robot we will use ROS2 Galactic and the Python Client Library. Please follow the directions written [here](https://iroboteducation.github.io/create3_docs/setup/ubuntu2004/) to set up ROS2 if you have not already.  


### Generally Important Information 

In any file, if a piece of code is written inside [] brackets it means you should fill it out with your unique namespace/package name/workspace etc. Do not include the [] when you run the code.

For example, if the namespace of my Create® 3 robot is JonSow. Then I would want to modify the code accordingly. 
```
ros2 topic echo /[Namespace]/battery_state
```
becomes
```
ros2 topic echo /JonSnow/battery_state
```
when you run it in your terminal. 
