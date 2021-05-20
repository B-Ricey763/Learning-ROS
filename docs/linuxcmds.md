# Useful Ros & Linux Commands
Lookup ROS packages
```bash
apt-cache search ros-noetic
```
Installed ROS package Dependencies
```bash
sudo rosdep install <package>
```
Creates a pdf of  the `transform_frame` graph 
```bash
rosrun tf2_tools view_frames.py
```
To view it, run
```bash
evince frames.pdf
```