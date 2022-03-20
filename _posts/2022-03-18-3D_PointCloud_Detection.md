---
layout: post
title:  "3D Pointcloud Detection"
date:   2022-03-18
excerpt: "Pointcloud; PointNet; DBSCAN; Classification;Kitti"
image: "/images/blog/3DPointcloudDetection/result.gif"
---

Lidar, or Vision, has always been a debatable question in the industry of autonomous driving. Compared with other camera sensors, Lidar is expensive, however,  the calculation of distance between objects is quite accurate. Let's see  Lidar's performance without the aid of vision. 

Here, we use kitti object detection dataset as our train and test ground. 3D point cloud data is used as input, and 2D image is used purely for visualization purpose. And use PointNet , a deep learning architecture specified designed for 3D point cloud data with very good performance on classification task.

Below is a pipeline for doing this object detection by cluster + classification method using pointcloud.



Since we cannot use the whole pointcloud image as the input Let's start by preparing our  training data. The goal of this step is to get separate pointcloud of different objects.  

Let's see a picture of the relationship of different coordinates in this kitti dataset.



1) Find the point cloud in camera field of view. Since Lidar can generate the data from 360 degree, and the camera can only see the front of the car, we don't need to deal with point cloud outside the field of view of camera.

   <div style="text-align: center"><img src="{{ "/images/blog/3DPointcloudDetection/FOV.jpg" | absolute_url }}" alt="" width = "600" /></div>


2. Extract all the groundtruth data in kitti labels. For this step, the center of the 3D bounding box in the camera frame and we need to transform them back to lidar frame to find corresponding points. We visualize the Cyclist in red,  Pedestrian in green, and Vehicles in blue.

   <div style="text-align: center"><img src="{{ "/images/blog/3DPointcloudDetection/gt.png" | absolute_url }}" alt="" width = "600" /></div>

3. Next, we need to remove ground and perform clustering strategy on the remaining data, and consider individual cluster as one object,  give all the objects label "Others". The clustering method I use is DBSCAN, a density-based spatial clustering of applications with noise.

<div style="text-align: center"><img src="{{ "/images/blog/3DPointcloudDetection/cluster.png" | absolute_url }}" alt="" width = "600"/></div>





