---
title: "YOLO for Tree Crown Segmentation"
excerpt: "Engaged in a collaborative project with **Manaaki Whenua – Landcare Research**, focusing on the image segmentation of individual tree crowns from aerial imagery in the Wellington region, 2022-2025<br/><br/><img src='/images/tree.png' width='750'>"
collection: projects
layout: single-project
---

## Project Overview

This collaborative research with **Manaaki Whenua – Landcare Research** focused on developing advanced AI models to segment individual tree crowns from aerial imagery in the Wellington region, New Zealand.
The overall goal of this project is to address these challenges by leveraging YOLO-based instance segmentation methods and tailoring it to the unique requirements of aerial tree crown identification and species classification. 

## Key Contributions
- Performed data pre-processing, analysis, and visualization, developing insightful visual representations to highlight key patterns and segmentation results.
- Developed **advanced deep learning models** for object detection and image segmentation.  
- Advanced **foundational research** through **novel algorithmic approaches**, with findings published in journals and conferences.
- Worked with superviors to **assess project progress** and communicated key findings through **reports and presentations**.  

## Methodology

- Proposed a new YOLO method for identifying individual tree crowns based on YOLOv7.
  - Introduced a specialized detection mechanism for small and medium tree crowns
  - Employed dense connectivity in the backbone to reuse feature maps across layers
  - Incorporated an efficient attention module to capture long-range dependencies.
  - Experiments on the Wellington aerial canopy dataset demonstrated that this method achieves higher detection and segmentation accuracies than other commonly used baselines.

- Proposed a new efficient YOLOv8 method, optimized for precise instance segmentation and species classification of tree crowns.
  - This method includes new schemes for selecting candidate positive samples for each instance and a refined network design tailored for small and medium tree crowns.
  - Adjustments in hyperparameters, particularly within the Task-Aligned Assigner, are also discussed to better suit canopy segmentation tasks.
  - Comprehensive experiments conducted on the canopy dataset demonstrated that the new approach not only outperforms a number of advanced methods in terms of the Box AP and Mask AP metrics but also achieves a substantial decrease in parameters and model complexity.

- Proposed a feature fusion technique based on the YOLOv8 architecture to address diverse canopy sizes.
  - Incorporated a feature fusion mechanism that includes both cross-scale and same-scale fusion methods, enhancing the model's ability to integrate information across different layers and scales.
  - Large convolution operations was employed to effectively extract key features, helping the model capture richer and deeper global information in the image.
  - Experimental results on the canopy dataset demonstrated that the new method further advances performance, marking a promising solution for accurate and efficient instance segmentation of individual tree crowns in aerial imagery.

## Achievements

- Achieved **precise tree crown prediction**, with **10% improvement in detection** and **8% improvement in segmentation accuracy**.  
- Successfully identified various tree species with high accuracy
- Developed models that work effectively across diverse landscapes including urban, suburban, and forest areas

## Tech Stack

- Python, GitHub, YOLO, Transformer, LaTeX

## Impact

This research contributes to better forest management, urban planning, biodiversity modeling, and pest control in New Zealand. The developed models help in efficient tree counting, species identification, and health monitoring across large areas.
