# rl-uav

# How to start


## 1. Install dependencies

```
sudo apt-get install ros-noetic-ecl-exceptions
sudo apt-get install ros-noetic-ecl-threads
sudo apt install ros-noetic-kobuki* ros-noetic-ecl-streams
sudo apt-get install ros-noetic-joy

```

## 2. start world with a turtlebot2
```
roslaunch turtlebot_gazebo turtlebot_world.launch 
```
or with a lidar
```
roslaunch turtlebot_gazebo h.launch 
```

## 3. keyboard move
```
roslaunch turtlebot_teleop keyboard_teleop.launch
```

# Reference

https://blog.csdn.net/weixin_44999897/article/details/128377100


https://blog.csdn.net/Changer_sun/article/details/79264388?spm=1001.2101.3001.6650.16&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-16-79264388-blog-114215939.235%5Ev38%5Epc_relevant_default_base3&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-16-79264388-blog-114215939.235%5Ev38%5Epc_relevant_default_base3&utm_relevant_index=23
