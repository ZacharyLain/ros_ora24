# ros_ora24

The ORA software for 2024.

Huh?

## To work on the code

- `mkdir ros2_ws && cd ros2_ws`
- `git clone https://github.com/oaklandrobotics/ros_ora24 src`
- code
- `colcon build && . install/setup.bash`

## To set up the dev environment

- Install ROS2 Humble on Ubuntu 22.04
  - https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html
- `echo "source /opt/ros/humble/setup.bash" >> .bashrc`
  - This wil make it so you don't have to do the `source` command every time you open a new terminal session
- `sudo apt install python3-colcon-common-extensions`
- `pip install -r requirements.txt`
  - If pip is not installed, `sudo apt install python3-pip`