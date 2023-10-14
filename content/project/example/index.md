---
slides: example
url_pdf: ""
summary: >-
  • Method overview:


  1. The semantic module only combines the ORB-SLAM3 and YOLOX-s

  2. The mapping module refers to a system for semantic Labelling 3D
     Point Cloud in vSLAM

     > 1. X. Qi, S. Yang, and Y. Yan, Deep Learning Based Semantic Labelling of 3D Point Cloud in Visual SLAM,
     >    10 2018, vol. 428, p. 012023.

  • Open source work:

  The work is open source on Github and presented on Bili (8000+v).
url_video: ""
date: 2023-10-14T03:46:56.053Z
external_link: ""
url_slides: ""
title: CDS-SLAM-Semantic-mapping-in-dynamic-environment
tags:
  - Deep Learning
links:
  - url: https://github.com/SlamMate/CDS-SLAM-Semantic-mapping-in-dynamic-environment
    icon_pack: fab
    icon: github
  - url: https://youtu.be/OxYHrIgqyJQ?si=KcRyw8GC9f-4Dkgd
    icon_pack: fab
    name: ""
    icon: youtube
  - url: https://www.bilibili.com/video/BV1St4y157qH/?share_source=copy_web&vd_source=12d45e19826de0471391d3db9d6c9491
    icon_pack: fab
    icon: bilibili
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
url_code: ""
---
This is my undergraduate dissertation. I deploy TensorRT optimized YOLOX in the front end of ORB-SLAM3 for object detection and eliminate all points belonging to the human bounding box. At the same time, the semantic information is sent to the mapping module to dye the 3D point cloud.