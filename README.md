# m_mh24
A  basic 6-DOF manipulator simulation platform using ROS-Gazebo-Moveit. (for completely beginners)

![image](https://github.com/lindaqqiu/m_mh24/blob/master/m_mh24/images/moveit.png)

>[The BaiduYun address of the demo video](https://pan.baidu.com/s/1WJx3cYXOpdEbxMX0lzY93A)
>code:216l
---
## System Environment
Ubuntu 18.04.1    ROS melodic    Gazebo 9.0    Moveit
## How To Use
If you want to see the robotic with the kinect 3D sensor, use this terminal command:  
`roslaunch m_mh24_gazebo m_mh24_bringup_moveit_kinect.launch`
 
To see the scene without the kinect, use the command:  
`roslaunch m_mh24_gazebo m_mh24_bringup_moveit.launch`  
  
---
To see the Gazebo scene only (without a moveit interface), use the command:  
`roslaunch m_mh24 m_mh24_gazebo_with_workpiece_kinect`  
or  
`roslaunch m_mh24 m_mh24_gazebo_with_workpiece`  
  
---
To just check the robotic model in rviz, use the command:  
`roslaunch m_mh24 display.launch`  
  
---
## Tutorial (Chinese version)
I prepared a tutorial which describes the process from the installation of Ubuntu to the completion of a simulation platform using ROS-Gazebo-Moveit.You can find this file in:  
`新手教程：从Ubuntu到ROS-Gazebo-Moveit机械臂运动规划仿真平台`  

