# Diff Drive description (Humble)
## Installation

Install the dependencies.
```
sudo rosdep init
rosdep update
rosdep install --from-paths src --ignore-src -r -y
```
## Build
```
colcon build
```
## Test
source dependencies first
```
source /usr/share/gazebo/setup.sh
source install/setup.bash
ros2 launch diff_drive_description display.launch.py
```