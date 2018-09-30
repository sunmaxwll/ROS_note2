# LiveCD sunMaxwell ROS KIT

# install mx_turtleBot package

## Manual

cd ~/mxBot_ws/src

git clone http://github.com/sunmaxwll/mx_turtleBot.git

cd ..

catkin_make

rospack profile

source devel/setup.bash

## Script

cd ~/

chmod +x install_mxBot.sh

./install_mxBot.sh

# USB Camera Demo

* Movidius NCS Demo

~/Desktop/Demo/NCS_SSDMobile_Demo.sh

~/Desktop/Demo/NCS_TinyYolo_Demo.sh

* openCL CAFFE Demo

~/Desktop/Demo/OpenCl_Yolo2_Demo.sh

* mxBot Device Demo

roslaunch mx_bringup rbc_mini_start.launch

# Realsense SR300/D415/D435

{DIR_DEMO}/*Demo_RS.sh

# RGBD-SLAM

roslaunch realsense_camera sr300_nodelet_rgbd.launch

cd ~/SLAM/rgbdslam_catkin_ws/

source devel/setup.bash 

roslaunch rgbdslam rgbdslam.launch

# sunMaxwell 阳光明媚 AT: 2018.06.07

# 这是秘密，我不告诉你。



