---
title: "DPL-SLAM: Enhancing Dynamic Point-Line SLAM through dense semantic methods"
publication_types:
  - "0"
authors:
  - Zhihao Lin
  - Qi Zhang
  - Zhen Tian
  - Peizhuo Yu
  - Jianglin Lan
publication: IEEE Sensors Journal
publication_short: IEEE Sensors Journal
abstract: The traditional visual Simultaneous Localization and Mapping (SLAM)
  systems rely on the static-world assumption and cannot handle dynamic objects.
  This paper presents a novel SLAM system, Semantic Point and Line Features SLAM
  (DPL-SLAM), that can handle dynamic environments and can be used for real-time
  operation. To handle dynamic objects, we apply object detection to identify 80
  categories within the scene and implement unique handling of features both
  within and outside the detected bounding boxes using Lucas-Kanade (LK) optical
  flow and epipolar constraint. Within bounding boxes, we propose an efficient
  local elimination algorithm to address features that violate the epipolar
  constraint. We designate nearby and intra-box regions that deviate from the
  constraint as potential dynamic areas, and conditionally eliminate features
  within these areas to varying extents, thus minimizing incorrect elimination
  of stable data associations. Outside the bounding boxes, non-compliant
  features are regarded as outliers and directly eliminated, making the system
  robust to unknown objects. We have evaluated DPL-SLAM on the TUM RGB-D and
  KITTI STEREO datasets and compared it with state-of-the-art SLAM systems. The
  results show that DPL-SLAM outperforms most SLAM systems in various dynamic
  scenarios and exhibits excellent robustness and realtime performance, thus
  effectively handling dynamic noise interference under indoor RGB-D and outdoor
  stereo modes. Finally, we conduct experiments in a real-world environment to
  verify the algorithm's effectiveness.
draft: false
featured: false
image:
  filename: null
  focal_point: Smart
  preview_only: false
date: 2024-03-19T15:05:06.323Z
---
