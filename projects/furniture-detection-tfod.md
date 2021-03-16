---
layout: project
type: project
image: images/furniture-detection-tfod.png
title: Furniture Detection TFOD
projecturl: https://github.com/rpnugroho/furniture-detection-tfod
permalink: projects/furniture-detection-tfod
# All dates must be YYYY-MM-DD format!
date: 2021-01-29
labels:
  - TensorFlow
  - Object Detection
  - TFServing
  - Streamlit
summary: Furniture detection using Tensorflow Object Detection API. Dataset was obtained from OpenImages and converted into TFRecord format. After training EfficientDet-D0 for 100k steps we got 17.1% mAP on test dataset. For deployment we use Docker and Streamlit for app demo.
---