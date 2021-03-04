# Map-My-World

### Project Purpose:
Simulated robot creates a 2D occupancy grid and 3D octomap from a gazebo world using the RTAB-Map package.

![](/pictures/mapping1.png)

![](/pictures/mapping2.png)

![](/pictures/mapping3.png)


To launch this project, in three seperate terminals use the following commands.
```
roslaunch my_robot world.launch
```

```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

```
roslaunch my_robot mapping.launch
```
