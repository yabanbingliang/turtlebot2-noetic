# How to start
The repository is to redeploy turtlebot2 in the environment of ubuntu20.04 ros noetic, and add an additional 2d lidar sensor on top of tb2.

## 1. Install dependencies

```
sudo apt install ros-noetic-kobuki-* -y
sudo apt install ros-noetic-ecl-streams -y
sudo apt install ros-noetic-depthimage-to-laserscan -y
sudo apt install ros-noetic-joy -y

```

## 2. add some gazebo models [[download](https://github.com/osrf/gazebo_models)]

```
unzip gazebo.zip -d ~/.gazebo/
```

## 3. start world with a turtlebot2
```
roslaunch turtlebot_gazebo turtlebot_world.launch 
```
or with a lidar
```
roslaunch turtlebot_gazebo h.launch 
```

## 4. keyboard move
```
roslaunch turtlebot_teleop keyboard_teleop.launch
```

# Reference

[1][Ubuntu 20.04 ROS_noetic安装Turtlebot2](https://blog.csdn.net/weixin_44999897/article/details/128377100)

[2][turtlebot_gazebo仿真添加激光雷达hokuyo_rplidar](https://blog.csdn.net/Changer_sun/article/details/79264388?spm=1001.2101.3001.6650.16&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-16-79264388-blog-114215939.235%5Ev38%5Epc_relevant_default_base3&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-16-79264388-blog-114215939.235%5Ev38%5Epc_relevant_default_base3&utm_relevant_index=23)


