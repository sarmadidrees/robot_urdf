# ROS Robot URDF
A ROS package for publishing Robot URDF with each joints and links. This package is specifically for IMRobot (a mobile robot project), which includes:
- 5 x MB7380 HRXL-MaxSonar-WRT
- 1 x RPLIDAR A2 360° Laser Scanner
- 1 x FLiR Lepton Thermal Imaging Camera
- 1 x MPU9250, a 9-axis Motion Processing Unit


#### Working Screenshots
```
rosrun tf view_frames
evince frames.pdf
```
![tf](https://user-images.githubusercontent.com/22538217/32210288-a2c8e1dc-be2e-11e7-966d-f85fd60e12e0.png)

```
rosrun rviz rviz
```
![rviz](https://user-images.githubusercontent.com/22538217/32209380-d6069e5e-be29-11e7-8be1-2521d7c2a841.png)

