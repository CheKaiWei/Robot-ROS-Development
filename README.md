# Robot-ROS-Development
__Update__ on 2019.5.29

__Project:__ Robot-ROS-Development

__environment__: matlab1018b   

## System:  
![Simulink](/img/system.png)  
whole system  

## 想法
其中机器人分为三个部分，感知层、决策层、执行层。感知层由视觉系统定位，决策层分为Global Planning和Loacal Planning以用于规划整体前进的速度
以及每个轮子前进的速度。执行层为理想电机，根据陀螺仪获取姿态，编码器获取距离，以用于调控其实际速度。

## 实际系统开发平台
感知层、决策层：嵌入式系统（暂时未定型号，树莓派或者S3C2440），ROS系统  
执行层：STM32

# Contact
Feel to contact me. My email is richardfeynman180778@gmail.com.
