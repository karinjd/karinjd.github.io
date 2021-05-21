---
title: "Towards Robust Visual Diver Detection Onboard Autonomous Underwater Robots:  Assessing the Effects of Models and Data"
collection: publications
permalink: /publication/diver_det
excerpt: 'In this paper, we present our approach for addressing robustness and correctness challenges in applying deep models to our particular vision problem: diver detection onboard autonomous underwater vehicles (AUVs).'
date: 2021-06-01
venue: 'Under Review'
paperurl: 'http://karinjd.github.io/files/diver_detection.pdf'
---
Abstract: Deep neural networks are the leading solution to the object detection problem. However, challenges arise when applying these networks to the kind of real-time, first-person video data that a robotic platform must process: specifically, detections may not be consistent from frame to frame, and ob- jects may frequently appear at viewpoints that are particularly challenging for the model, resulting in inaccurate detections. In this paper, we present our approach for addressing these challenges for our particular vision problem: diver detection onboard autonomous underwater vehicles (AUVs). We begin by producing and releasing a dataset of approximately 105,000 annotated images of divers sourced from videos in order to address the challenge of learning a wide variety of object rotations and translations. This is one of the largest and most varied diver detection datasets ever created, and we compare models trained and tested on both our dataset and a previous dataset to demonstrate that our dataset improves the state-of- the-art in diver detection. Then, in order to choose an object detection model that produces detections that are consistent from frame to frame, we evaluate several state-of-the-art object detection models on the temporal stability of their detections in addition to the typical accuracy and efficiency metrics, mean average precision (mAP) and frames per second. Importantly, our results showed that models with the highest mAP do not also have the highest temporal stability.

[Download paper here](http://karinjd.github.io/files/diver_detection.pdf)
