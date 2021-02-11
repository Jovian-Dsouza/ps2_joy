
## Installation
```
sudo apt-get install ros-$ROS_DISTRO-joy -y
sudo apt-get install ros-$ROS_DISTRO-teleop-twist-joy -y
sudo apt-get install jstest-gtk -y

cd /opt/ros/$ROS_DISTRO/share
sudo git clone https://github.com/Jovian-Dsouza/ps2_joy

#Restart terminal session
```

## Configure the joystick
```
ls /dev/input/

# Where X refers to your joystick number

sudo jstest /dev/input/jsX 
sudo chmod a+rw /dev/input/jsX

```
