---
title: Semantic SLAM for mobile robots in dynamic environments based on visual
  camera sensors
publication_types:
  - "2"
authors:
  - admin
  - Changdi Li
publication_short: MST
abstract: Visual simultaneous localization and mapping (vSLAM) is inherently
  constrained by the static world assumption, which renders success in the
  presence of dynamic objects rather challenging. In this paper, we propose a
  real-time semantic vSLAM system designed for both indoor and outdoor dynamic
  environments. By employing object detection, we identify 80 categories and
  utilize motion consistency checks to pinpoint outliers in each image. Distinct
  methods are presented for examining the motion states of humans and other
  objects. For detected humans, an algorithm is introduced to assess whether an
  individual is seated, subsequently dividing the bounding boxes of seated
  individuals into two parts based on human body proportions. We then use the
  same threshold values for standing individuals to determine the states of the
  two boxes belonging to seated individuals. For non-human objects, we propose
  an algorithm capable of automatically adjusting the threshold values for
  different bounding boxes, thereby ensuring consistent detection performance
  across various objects. Ultimately, we retain points within static boxes
  contained in dynamic boxes while eliminating other points in dynamic boxes to
  benefit from a larger number of detected categories. Our SLAM is evaluated on
  indoor TUM and Bonn RGB-D datasets, with further testing conducted on the
  outdoor stereo KITTI dataset. The results reveal that our SLAM outperforms
  most SLAM systems in dynamic environments. Moreover, we test our system in
  real-world environments with a monocular camera, demonstrating its robustness
  and universality across diverse settings.
draft: false
featured: true
tags: []
url_pdf: "https://iopscience.iop.org/article/10.1088/1361-6501/acd1a4/pdf"
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
summary: This work focuses on proposing a dynamic vSLAM algorithm for dense
  object detection. Percentage thresholding and elimination of static boxes
  within the dynamic box are used to retain static keypoints as much as
  possible.
url_dataset: ""
url_project: ""
url_source: ""
url_video: "https://youtu.be/9g6-N-uYeno?si=-wOTaVoZFuqZdMWX"
author_notes:
  - First and corresponding author
  - Second author
doi: "10.1088/1361-6501/acd1a4"
publication: Measurement Science and Technology, Volume 34, Number 8
projects: []
date: 2023-05-11T01:51:00.000Z
url_slides: ""
publishDate: 2023-05-11T00:00:00.000Z
url_poster: ""
url_code: https://github.com/SlamMate/Universal-outdoor-indoor-multi-camera-vSLAM-based-on-pre-trained-models
---
