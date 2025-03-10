---
layout: archive
title: "Skills"
permalink: /skills/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="skills-container">
  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Programming Languages</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag skill-tag-highlighted">Python</span>
      <span class="skill-tag">Java</span>
      <span class="skill-tag">C/C++</span>
      <span class="skill-tag">MATLAB</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Data Science & Analysis</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag">Pandas</span>
      <span class="skill-tag">NumPy</span>
      <span class="skill-tag">SciPy</span>
      <span class="skill-tag">SQL</span>
      <span class="skill-tag">Data Visualization</span>
      <span class="skill-tag">Statistical Analysis</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Machine Learning & AI</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag">Deep Learning</span>
      <span class="skill-tag">Computer Vision</span>
      <span class="skill-tag">Image Processing</span>
      <span class="skill-tag">Neural Networks</span>
      <span class="skill-tag">YOLO Models</span>
      <span class="skill-tag">Transformer Models</span>
      <span class="skill-tag">Object Detection</span>
      <span class="skill-tag">Image Segmentation</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Frameworks & Libraries</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag skill-tag-highlighted">PyTorch</span>
      <span class="skill-tag">TensorFlow</span>
      <span class="skill-tag">OpenCV</span>
      <span class="skill-tag">Scikit-learn</span>
      <span class="skill-tag">Matplotlib</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Software & Tools</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag">Jupyter Notebook</span>
      <span class="skill-tag">Visual Studio</span>
      <span class="skill-tag">PyCharm</span>
      <span class="skill-tag">Microsoft Office</span>
      <span class="skill-tag">Photoshop</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Version Control & Collaboration</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag">GitHub</span>
      <span class="skill-tag">GitLab</span>
    </div>
  </div>

  <div class="skills-card">
    <div class="skills-card-header">
      <h2>Soft Skills</h2>
    </div>
    <div class="skills-card-content">
      <span class="skill-tag">Teamwork</span>
      <span class="skill-tag">Leadership</span>
      <span class="skill-tag">Research</span>
      <span class="skill-tag">Presentation</span>
      <span class="skill-tag">Teaching</span>
      <span class="skill-tag">Training</span>
      <span class="skill-tag">Consultation</span>
    </div>
  </div>
</div>

<style>
  .skills-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
  }
  
  .skills-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .skills-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }
  
  .skills-card-header {
    background: linear-gradient(135deg, #0366d6, #2e89ff);
    padding: 12px 20px;
  }
  
  .skills-card-header h2 {
    margin: 0;
    color: white;
    font-size: 1.3em;
  }
  
  .skills-card-content {
    padding: 15px 20px;
    background-color: #f8f9fa;
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }
  
  .skill-tag {
    display: inline-block;
    background-color: white;
    padding: 5px 12px;
    border-radius: 20px;
    font-size: 0.9em;
    border: 1px solid #e0e0e0;
    transition: all 0.2s ease;
  }
  
  .skill-tag:hover {
    background-color: #0366d6;
    color: white;
    transform: scale(1.05);
  }
  
  .skill-tag-highlighted {
    background-color: #0366d6;
    color: white;
    border-color: #0366d6;
    font-weight: bold;
  }
</style>
