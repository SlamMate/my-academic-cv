---
title: "SLAM2: Simultaneous Localization and Multimode Mapping for indoor
  dynamic environments"
publication_types:
  - "0"
authors:
  - Zhihao Lin
  - Qi Zhang
  - Zhen Tian
  - Peizhuo Yu
  - Ziyang Ye
  - Hanyang Zhuang
  - Jianglin Lan
doi: https://doi.org/10.1016/j.patcog.2024.111054
publication: Pattern Recognition
abstract: >
  Traditional visual Simultaneous Localization and Mapping (SLAM) methods based
  on point features are often limited by strong static assumptions and texture
  information, resulting in inaccurate camera pose estimation and object
  localization.To address these challenges, we present SLAM

  , a novel semantic RGB-D SLAM system that can obtain accurate estimation of the camera pose and the 6DOF pose of other objects, resulting in complete and clean static 3D model mapping in dynamic environments. Our system makes full use of the point, line, and plane features in space to enhance the camera pose estimation accuracy. It combines the traditional geometric method with a deep learning method to detect both known and unknown dynamic objects in the scene. Moreover, our system is designed with a three-mode mapping method, including dense, semi-dense, and sparse, where the mode can be selected according to the needs of different tasks. This makes our visual SLAM system applicable to diverse application areas. Evaluation in the TUM RGB-D and Bonn RGB-D datasets demonstrates that our SLAM system achieves the most advanced localization accuracy and the cleanest static 3D mapping of the scene in dynamic environments, compared to state-of-the-art methods. Specifically, our system achieves a root mean square error (RMSE) of 0.018 m in the highly dynamic TUM w/half sequence, outperforming ORB-SLAM3 (0.231 m) and DRG-SLAM (0.025 m). In the Bonn dataset, our system demonstrates superior performance in 14 out of 18 sequences, with an average RMSE reduction of 27.3% compared to the next best method.
draft: false
featured: true
image:
  filename: 1-s2.0-s0031320324008057-gr1_lrg.jpg
  focal_point: Smart
  preview_only: false
date: 2024-10-01T06:01:59.409Z
---
