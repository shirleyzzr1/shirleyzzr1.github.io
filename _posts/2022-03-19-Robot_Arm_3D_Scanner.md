---
layout: post
title:  "Robot Arm 3D Scanner"
date:   2022-03-19
excerpt: "ROS; MoveIt; PCL; Python; C++"
image: "/images/blog/fakescanner/scanner.gif"
---

<div style="text-align: center"><img src="{{ "/images/blog/fakescanner/fake_scanner.gif" | absolute_url }}" alt="" width = "600"/></div>

This project is a ROS project for ME495_embedded system at Northwestern University. The goal of the project is about using an adroit robot arm to hold the object and use a fixed RealSense  D435 camera to capture the 3D point cloud of this project.

This is the flow chart of the project

<div style="text-align: center"><img src="{{ "/images/blog/fakescanner/flow_chart.gif" | absolute_url }}" alt="" width = "600"/></div>

There are two main parts for this project, control of the robot arm and  process of the point cloud data. Two different packages deal with these two aspects.

- **realsense_reader**

  Starting the realsense camera and process the pointcloud data to fuse the lidar data

- **adroit_move**

  Control the movement of the adroit arm

For more details: [click here to go to github repository](https://github.com/shirleyzzr1/fake_scanners)