---
layout: archive
title: "Skills"
permalink: /skills/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<div class="skills-wrapper">
  <div class="skills-category">
    <h3><i class="fas fa-code" style="color: #0366d6;"></i> Programming Languages</h3>
    <ul>
      <li><strong>Python</strong> (Advanced)</li>
      <li>Java</li>
      <li>C/C++</li>
      <li>MATLAB</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-database" style="color: #0366d6;"></i> Data Science & Analysis</h3>
    <ul>
      <li>Pandas, NumPy, SciPy</li>
      <li>SQL for database querying</li>
      <li>Data cleaning & preprocessing</li>
      <li>Statistical analysis</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-brain" style="color: #0366d6;"></i> Machine Learning & AI</h3>
    <ul>
      <li>Deep Learning</li>
      <li>Computer Vision & Image Processing</li>
      <li>YOLO models, Transformer models</li>
      <li>Neural Networks & Optimization Algorithms</li>
      <li>Object Detection & Image Segmentation</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-tools" style="color: #0366d6;"></i> Frameworks & Libraries</h3>
    <ul>
      <li><strong>PyTorch</strong></li>
      <li>TensorFlow</li>
      <li>OpenCV</li>
      <li>Scikit-learn</li>
      <li>Matplotlib</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-desktop" style="color: #0366d6;"></i> Software & Tools</h3>
    <ul>
      <li>Jupyter Notebook</li>
      <li>Visual Studio, PyCharm</li>
      <li>Microsoft Office</li>
      <li>Photoshop</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-code-branch" style="color: #0366d6;"></i> Version Control & Collaboration</h3>
    <ul>
      <li>GitHub</li>
      <li>GitLab</li>
    </ul>
  </div>

  <div class="skills-category">
    <h3><i class="fas fa-users" style="color: #0366d6;"></i> Soft Skills</h3>
    <ul>
      <li>Teamwork & Leadership</li>
      <li>Research & Presentation</li>
      <li>Teaching & Training</li>
      <li>Consultation</li>
    </ul>
  </div>
</div>

<style>
  .skills-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
  }
  
  .skills-category {
    flex: 1 0 45%;
    min-width: 260px;
    background-color: #f8f9fa;
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 20px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
  }
  
  .skills-category h3 {
    color: #333;
    border-bottom: 2px solid #0366d6;
    padding-bottom: 8px;
    margin-bottom: 12px;
  }
  
  .skills-category ul {
    list-style-type: none;
    padding-left: 10px;
  }
  
  .skills-category ul li {
    padding: 5px 0;
    position: relative;
  }
  
  .skills-category ul li:before {
    content: "•";
    color: #0366d6;
    font-weight: bold;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }
  
  @media only screen and (max-width: 600px) {
    .skills-category {
      flex: 1 0 100%;
    }
  }
</style>
