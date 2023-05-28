# ROS NOETIC KURULUMU

# GEREKLİLİKLER

1- Ubuntu 20.04

# KURULUM

1- `sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`

2- `curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -`

3- `sudo apt update`

4- `sudo apt install ros-noetic-desktop-full`

5- `nano ~/.bashrc` komutu ile .bashrc dosyası açılır ve aşağıdaki satır eklenir:

source /opt/ros/noetic/setup.bash

6- `sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential`

7- `sudo rosdep init`

8- `rosdep update`
