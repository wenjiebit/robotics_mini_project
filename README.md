# robotics_mini_project
Mini project in roboticas &amp; AI. Working with ROS, gazebo, openCV (python).

# Install
make sure you have ~/catkin_ws and all the usual ric reqs

clone https://github.com/robotican/ric into catkin_ws/src/ric:

```
cd ~/catkin_ws/src/
git clone https://github.com/robotican/ric
```

download this folder into catkin_ws/src/project:

```
cd ~/catkin_ws/src/
git clone https://github.com/Lagogo25/robotics_mini_project.git
mv robotics_mini_project project (or any other way you would like to rename the folder you just cloned into 'project')
```

make sure you have in .bashrc : source ~/catkin_ws/devel/setup.bash
```
catkin_make 
rospack list (make sure you see "ric" & “project”)
```
# Launch
```
cd ~/catkin_ws/src/project
launch.py (or: python launch.py)
```
Note: the launch files automatically runs the the command:
roslaunch project our_komodo.launch
with random position for the robot, in a random world(= random cube orders) and then run our_robot.py which handles the camera and laser messages.

