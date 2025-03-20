---
title: "Glass Flaw Detection and Positioning System"
excerpt: "Engaged in a project with **Laiwu Lianyun Glass Company** in **China**, focusing on precise detection and real-time positioning of flaws in various types of glass, 2021<br/><br/><img src='/images/boli.png' width='750'>"
collection: projects
layout: single-project
---

## Project Overview

This project was developed in collaboration with **Laiwu Lianyun Glass Company** in China to create an automated system for detecting and precisely locating flaws in various types of glass products. Despite advances in glass manufacturing technology, defects like bubbles and inclusions inevitably occur during processes such as vacuum magnetron sputtering, affecting both performance and appearance. Manual inspection, the prevailing method, was becoming inadequate due to increased production speeds and quality requirements.

## Key Contributions  
- Contributed to team efforts in **building a specialized dataset** for glass defect detection, including:  
  - Collecting data from production lines
  - Employing **image processing techniques** to enhance defect features  
  - Developing robust image preprocessing solutions including color recognition, area and length measurement, image enhancement, edge sharpening, and noise reduction
  - Establishing a comprehensive database categorized by defect types and product models
- Developed a **comprehensive AI-based pipeline** using **deep learning models (YOLO)** optimized for small object detection challenges.
- Designed a multi-scale learning network to identify and quantify critical image features through multi-scale context fusion.
- Implemented a dual attention mechanism incorporating both Channel Attention Module and Spatial Attention Module to effectively filter noise and enhance feature representation.
- Created a complete optical imaging solution specifically tailored for glass defect visualization.

## Methodology
- Designed a specialized optical imaging setup with blue coaxial lighting that showed excellent visibility for most glass defects
- Implemented a non-contact system leveraging glass transparency properties to prevent secondary damage
- Developed a right-angle conveyor design to capture images of all four edges without stopping
- Applied advanced image processing techniques for data preprocessing and augmentation
- Utilized LabelIMG software to perform 2D rectangular box marking of various defect types
- Constructed a database with thousands of defect samples after thorough data cleaning
- Implemented a One-Stage detector with multi-scale learning and mixed attention mechanisms to balance speed and accuracy

## Achievements  
- Achieved a **detection rate of 93%** and a **precision rate of 95%** in test environments.
- Successfully deployed the system in production environments operating at full manufacturing speeds.
- Created a complete detection workflow with integrated automated marking systems.
- Developed a model capable of detecting small-target defects that are difficult to observe with the naked eye.
- System supports real-time detection with edge computing deployment on NVIDIA Jetson Xavier modules offering 32 TOPS of AI performance.

## Tech Stack
- PyTorch, OpenCV, Python, YOLO, Attention Mechanisms.

## Impact
The implementation of this automated glass flaw detection system significantly improved product quality while reducing production costs for Laiwu Lianyun Glass Company. The system is now widely applied in industrial machine vision applications for flat glass, specialty glass, and decorative glass inspection. Its combined detection speed and accuracy have delivered exceptional results in real-world applications.
