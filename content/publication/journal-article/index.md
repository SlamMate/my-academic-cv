---
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
slides: example
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - admin
  - Changdi Li
author_notes:
  - First and corresponding author
  - Second author
publication: Measurement Science and Technology, Volume 34, Number 8
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Semantic SLAM for mobile robots in dynamic environments based on visual
  camera sensors
doi: " 10.1088/1361-6501/acd1a4"
featured: false
tags: []
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
  focal_point: ""
  preview_only: false
date: 2015-09-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
