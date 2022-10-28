# Awesome-AutoLabeling-tools
Papers, code and datasets about deep learning data auto-labeling.

## Introduction
>In practice, the data of autonomous driving is very important, and how to get high-quality data integration efficiently and cost-effectively is the core competitiveness of autonomous driving companies.

>With the continuous development of autonomous driving perception technology, the requirements for annotation are getting higher and higher, and many annotation tasks are getting more and more difficult. Camera/Lidar joint labeling, 3d semantic segmentation, how to complete the automated labeling of the vector space, currently do not see any companies can do.

>Automatic labeling algorithm (auto-labeling) is actually a high-precision true value generation algorithm, can not be limited by the arithmetic power of the car, and can use the full time series of data to jointly optimize the results. Because it is offline, the accuracy is as high as it can be. Such a system, in addition to automated labeling/pre-labeling, also has many other roles, such as mining the corner case, guiding the vehicle-side model training, etc.

Here are some resources about deep learning data auto-labeling.

## Paper
#### Dynamic object auto-labeling (car, people, etc...)
- [Autolabeling 3D Objects with Differentiable Rendering of SDF Shape Priors](https://arxiv.org/abs/1911.11288), Toyota
- [Offboard 3D Object Detection from Point Cloud Sequences](https://arxiv.org/abs/2103.05073), Waymo
- [Auto4D: Learning to Label 4D Objects from Sequential Point Clouds](https://arxiv.org/abs/2101.06586), Waymo
#### Static object auto-labeling (tree, lane, etc...)
- [HDMAPNet](https://arxiv.org/abs/2107.06307), Mars Lab
- [VectorMapNet](https://arxiv.org/abs/2206.08920), Mars Lab
- [Full Surround Monodepth from Multiple Cameras](https://arxiv.org/abs/2104.00152), Toyota
- [Multi-Frame Self-Supervised Depth Estimation with Transformers](https://arxiv.org/abs/2204.07616), Toyota
- [3D Packing for Self-Supervised Monocular Depth Estimation](https://arxiv.org/abs/1905.02693), Toyota

## Survey
#### Dynamic object auto-labeling (car, people, etc...)
None
#### Static object auto-labeling (tree, lane, etc...)
- [High-Definition Map Generation Technologies For Autonomous Driving: A Review](https://arxiv.org/abs/2206.05400)

## Blog 
- [Bag of algorithms- autolabeling](https://zhuanlan.zhihu.com/p/533907821)
- [Tesla - autolabeling](https://zhuanlan.zhihu.com/p/466426243)
- [Tusimple - autolabeing](https://zhuanlan.zhihu.com/p/541893317)

## Video
- [RoboSense Inc - autolabeling](https://www.bilibili.com/video/BV1gK4y1x7Yh?from=search&seid=6201001844239327003&spm_id_from=333.337.0.0&vd_source=d6d7e511367717333c372785d76ae938)

## Codebase
- [Simulation - autolabeling](https://github.com/UsmanJafri/LiDAR-GTA-V)
- [Segmentation - autolabeling](https://github.com/PRBonn/auto-mos)
- [Sequence segmentation - autolabeling](https://github.com/Likarian/AutomaticLabeledLiDARSequence)
- [Depth - autolabeling](https://github.com/TRI-ML/vidar)

## Acknowlegement
[Chaikening - zhihu](https://zhuanlan.zhihu.com/p/533907821)
