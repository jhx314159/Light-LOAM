# Light-LOAM
News: Our paper has been accepted by the RA-L journal! 
This is the implementation for the Paper ``Light-LOAM: A Lightweight LiDAR Odometry and Mapping based on Graph-Matching''. This code is modified from [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM).

## Requirements
* PCL 1.10
* ROS
* Ceres 1.14.x

## git指令

```bash
git add .
git commit -m '修改lioloc.cpp，支持p2s和GICP分开执行4'
git push origin main
```
## 编译运行指令

```bash
catkin_make -j10
source devel/setup.bash
roslaunch light_loam light_loam-velodyne_guangzhou_port.launch
```

## Introduction
This is the beta version, and the final implementation code is coming soon. The research paper [Light-LOAM: A Lightweight LiDAR Odometry and Mapping based on Graph-Matching](https://arxiv.org/abs/2310.04162) is now availble on arXiv.

## Citation

If you take pieces from our system in your research, please consider citing the [paper](https://arxiv.org/abs/2310.04162):

```
@ARTICLE{10439642,
  author={Yi, Shiquan and Lyu, Yang and Hua, Lin and Pan, Quan and Zhao, Chunhui},
  journal={IEEE Robotics and Automation Letters}, 
  title={Light-LOAM: A Lightweight LiDAR Odometry and Mapping Based on Graph-Matching}, 
  year={2024},
  volume={9},
  number={4},
  pages={3219-3226},
  keywords={Simultaneous localization and mapping;Feature extraction;Point cloud compression;Reliability;Odometry;Laser radar;Robots;SLAM;localization;data association},
  doi={10.1109/LRA.2024.3367268}}

```
---------

## Acknowledgements
Thanks for [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM).


