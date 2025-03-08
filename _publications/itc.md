---
title: "YOLO-ITC: A New YOLO Method for Instance Segmentation of Individual Tree Crowns."
collection: publications
category: manuscripts
permalink: /publication/2025-02-01-itc-instance-segmentation
date: 2025-03-06
authors:
  - "Ziyi Sun"
  - "[Bing Xue](https://people.wgtn.ac.nz/bing.xue)"
  - "[Mengjie Zhang](https://people.wgtn.ac.nz/mengjie.zhang)"
  - "[Jan Schindler](https://www.landcareresearch.co.nz/about-us/our-people/jan-schindler)"
venue: "IEEE Transactions on Emerging Topics in Computational Intelligence"
paperurl: "[https://doi.org/10.1109/TETCI.2025.3543833](https://doi.org/10.1109/TETCI.2025.3543833)"
---

The instance segmentation task of individual tree crowns is an important real-world application that facilitates forest management, carbon storage estimation, and biodiversity modelling. Recently, Convolutional Neural Networks (CNNs) have achieved great success in computer vision. Several efforts have applied CNNs to perform instance segmentation of tree canopies. However, the existing CNN works rarely consider instance segmentation and species classification of densely distributed small and medium tree crowns. YOLO, as a fast and effective method, shows promising results in the field of instance segmentation and canopy detection and segmentation. We utilize a tree crown dataset from Wellington, Aotearoa, New Zealand, based on aerial imagery which contains small and medium-sized tree objects distributed across a diverse rural landscape ranging from isolated trees to dense forest stands. We propose a new YOLO method for individual tree crowns (ITC) based on YOLOv7, named YOLO-ITC. Specifically, a new detection design targeting small and medium trees is first proposed. Based on this, we propose a Dense Block module for the main block of the backbone in a densely connected way, where the previous features are reused to aggregate more useful information. Finally, efficient attention is embedded in the Dense Block to capture the globally long-range dependencies. Extensive experimental results show that the proposed method, YOLO-ITC, achieves both higher detection and mask accuracy over other commonly used baseline models.


