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

# Adaptive HRI Library (自适应机器人交互软件库)

roscore

roslaunch usb_cam usb_cam-test.launch

cd /home/intel/ai_ws/sdk_release/build/devel/lib/person_id

./mobilenet_ssd_ncs

打开新的终端：
cd /home/intel/ai_ws/sdk_release/build/devel/lib/person_id

./body_id

打开新的终端：
cd /home/intel/ai_ws/sdk_release/build/devel/lib/person_id

./face_id

打开新的终端：
cd /home/intel/ai_ws/sdk_release/build/devel/lib/person_id

./fusion

启动UI界面：

roslaunch rosbridge_server rosbridge_websocket.launch

cd /home/intel/ai_ws/sdk_release/launch

roslaunch web_video_server.launch

用浏览器打开：/home/intel/ai_ws/sdk_release/ui/person_identify.html

# sunMaxwell 阳光明媚 AT: 2018.09.05



