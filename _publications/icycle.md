---
title: "ICycleGAN: Single Image Dehazing Based on Iterative Dehazing Model and CycleGAN"
collection: publications
category: manuscripts
permalink: /publication/2021-02-01-yolov8e-instance-segmentation
date: 2021-02-01 
authors:
  - "Ziyi Sun"
  - "Yunfeng Zhang"
  - "Fangxun Bao"
  - "Kai Shao"
  - "Xinxin Liu"
  - "Caiming Zhang"
venue: "Computer Vision and Image Understanding"
paperurl: "https://doi.org/10.1016/j.cviu.2020.103133"
---

The current competitive approaches to restoring haze-free images are mainly based on physical models and learning methods. Maintaining detail information of the image while thoroughly removing fog is a challenging task in single-image dehazing. In this paper, by embedding an iterative dehazing model into the generative process of the Cycle-Consistent Adversarial Network (CycleGAN), we propose a model named ICycleGAN that maintains the defogging thoroughness of the learning-based dehazing method while retaining the good fidelity of the physical model-based dehazing method. Moreover, the proposed ICycleGAN does not require pairs of hazy and relative haze-free images for training. In addition, we develop a detail information-consistency loss that preserves more textural details and color information; this loss is obtained based on the physical features of the hazy image. To recover the high-resolution images, we enlarge the generated images using rational fractal interpolation, which restores fine textures and sharp edges. Extensive comparison results show that the proposed method produces high-quality clear images that are both quantitatively and qualitatively competitive with other state-of-the-art methods.


