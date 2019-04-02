
:white_check_mark: Tested with ROS Indigo and Velodyne VLP16. [(Screencast)](https://youtu.be/o1cLXY-Es54)

All sources were original taken from [ROS documentation](http://docs.ros.org/indigo/api/loam_velodyne/html/files.html) and developed by Zhong, from RIVeR Lab, Northeastern University

How to build with catkin:

```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/laboshinl/loam_velodyne.git
$ cd ~/catkin_ws
$ catkin_make -DCMAKE_BUILD_TYPE=Release 
$ source ~/catkin_ws/devel/setup.bash
```

Running:
```
roslaunch loam_velodyne loam_velodyne.launch
```

In second terminal play sample velodyne data from a rosbag, and replace "velodyne.bag" with "my.bag"
```
rosbag play ~/Downloads/velodyne.bag 
```

