# AVP_SLAM_ROS
    停车场环境中的语义建图与定位算法，代码实现参考cartographer。
    [video](https://www.bilibili.com/video/BV1aG4y1i7EC?share_source=copy_web&vd_source=1cd3f6f1bab3232928b0a4cc0ae193ad)

## 1.Prerequisites
    1.1 开发于ubuntu18.04 + ros melodic
    1.2 依赖库 ceres-solver

## 2.Build on Ros
    cd ~/catkin_ws/src
    git clone https://github.com/guyupan1911/AVP_SLAM_ROS.git
    cd ../
    catkin_make
    source devel/setup.bash

## 3.run semantic mapping
    roslaunch avp mappig
