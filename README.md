* Get the Turtlebot packages in VirtualBox, Ubuntu 20.
```
cd ~/
mkdir -p ros_ws/src/
git clone https://github.com/ROBOTIS-GIT/turtlebot3.git
cd ..
catkin_make
```

* In VirtualBox, get the ROS-TCP-Endpoint repo in your ros_ws
```
cd ros_ws/src/
git clone https://github.com/Unity-Technologies/ROS-TCP-Endpoint.git
cd ..
catkin_make
```

