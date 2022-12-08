# nav2_simulation

step1：
rosdep install -y -r -q --from-paths src --ignore-src --rosdistro foxy

step2:
colcon build

step3:
source /install/setup.bash

step4:
ros2 launch neor_gazebo
