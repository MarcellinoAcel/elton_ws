# Behavior Tree using Groot2
---

## System Requirements

- Ubuntu 22.04  
- ROS 2 (Humble recommended)
- Gazebo classic

---

## Install behaviortree-cpp-v3

```
sudo apt update
sudo apt install ros-humble-behaviortree-cpp-v3
```

## Install Groot2

install the Groot2 using this link https://www.behaviortree.dev/groot

## Clone this repo
```
git clone https://github.com/MarcellinoAcel/elton_ws.git 
cd elton_ws
source install/setup.bash
colcon build
```

## run the orb_slam
```
cd ~/elton_ws
```
```
./elton_run.sh
```