---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-section">
  <h2 class="cv-section-heading">Work Experience</h2>
  <div class="cv-entry">
    <h3>📌 Research Assistant (Mar 2025 - Present)</h3>
    <p class="cv-institution"><strong>Victoria University of Wellington</strong></p>
    <p class="cv-details"><em>Supervisors: Bing Xue, Mengjie Zhang</em></p>
  </div>

  <div class="cv-entry">
    <h3>📌 Intern at Digital & AI Team (Sep 2024 - Mar 2025)</h3>
    <p class="cv-institution"><strong>Callaghan Innovation</strong></p>
    <ul class="cv-details-list">
      <li>Engaged in the <strong>GovGPT</strong> and <strong>PaperBoi (Science-Paper Conversational Agent) projects</strong>.</li>
      <li>Enhanced large language model responses by fine-tuning the retrieval-augmented generation (RAG) component, focusing on retrieval improvements and prompt engineering.</li>
    </ul>
  </div>

  <div class="cv-entry">
    <h3>📌 Doctoral Researcher (Oct 2021 - Feb 2025)</h3>
    <p class="cv-institution"><strong>Victoria University of Wellington</strong></p>
    <ul class="cv-details-list">
      <li>Collaborated with <strong>Manaaki Whenua – Landcare Research</strong> to develop advanced AI models for segmenting individual tree crowns from aerial imagery in the Wellington region.</li>
      <li>Worked with the team to assess project progress and communicated key findings through reports and presentations.</li>
      <li><em>Supervisors: Bing Xue, Mengjie Zhang, Jan Schindler</em></li>
    </ul>
  </div>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Projects</h2>
  <div class="cv-projects">
    {% for post in site.projects reversed %}
      <div class="cv-project-item">
        <h3><a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a></h3>
        {{ post.excerpt | markdownify | remove: '<p>' | remove: '</p>' }}
      </div>
    {% endfor %}
  </div>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Skills</h2>
  <div class="skills-container">
    <div class="skills-card">
      <div class="skills-card-header">
        <h3>Programming Languages</h3>
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
        <h3>Data Science & Analysis</h3>
      </div>
      <div class="skills-card-content">
        <span class="skill-tag">Pandas</span>
        <span class="skill-tag">NumPy</span>
        <span class="skill-tag">SciPy</span>
        <span class="skill-tag">SQL</span>
        <span class="skill-tag">Data Visualization</span>
      </div>
    </div>

    <div class="skills-card">
      <div class="skills-card-header">
        <h3>Machine Learning & AI</h3>
      </div>
      <div class="skills-card-content">
        <span class="skill-tag">Deep Learning</span>
        <span class="skill-tag">Computer Vision</span>
        <span class="skill-tag">YOLO Models</span>
        <span class="skill-tag">Transformer Models</span>
        <span class="skill-tag">Object Detection</span>
        <span class="skill-tag">Image Segmentation</span>
      </div>
    </div>

    <div class="skills-card">
      <div class="skills-card-header">
        <h3>Frameworks & Libraries</h3>
      </div>
      <div class="skills-card-content">
        <span class="skill-tag skill-tag-highlighted">PyTorch</span>
        <span class="skill-tag">TensorFlow</span>
        <span class="skill-tag">OpenCV</span>
        <span class="skill-tag">Scikit-learn</span>
        <span class="skill-tag">Matplotlib</span>
      </div>
    </div>
  </div>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Publications</h2>
  <ul class="cv-list">
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Talks</h2>
  <ul class="cv-list">
    {% for post in site.talks reversed %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}
  </ul>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Education</h2>
  <div class="cv-entry">
    <h3>📌 PhD in Engineering and Computer Science</h3>
    <p class="cv-institution"><strong>Victoria University of Wellington</strong> | 🎯 <em>Expected 2025</em></p>
  </div>

  <div class="cv-entry">
    <h3>📌 MSc in Computer Science and Technology</h3>
    <p class="cv-institution"><strong>Shandong University of Finance and Economics</strong> | 🎯 <em>2021</em></p>
  </div>

  <div class="cv-entry">
    <h3>📌 BSc in Computer Science and Technology</h3>
    <p class="cv-institution"><strong>Shandong University of Finance and Economics</strong> | 🎯 <em>2018</em></p>
  </div>
</div>

<div class="cv-section">
  <h2 class="cv-section-heading">Interests</h2>
  <div class="interests-container">
    <div class="interest-category">
      <h3>Outdoor Activities</h3>
      <p>Hiking 🚶, Fishing 🎣, Cycling 🚴, Swimming 🏊</p>
    </div>
    
    <div class="interest-category">
      <h3>Intellectual Hobbies</h3>
      <p>Reading 📖, Researching 🧠</p>
    </div>
    
    <div class="interest-category">
      <h3>Sports & Fitness</h3>
      <p>Badminton 🏸, Gym 💪</p>
    </div>
  </div>
</div>

<style>
  .cv-section {
    margin-bottom: 2rem;
    padding-bottom: 1rem;
    border-bottom: 1px solid #f2f2f2;
  }
  
  .cv-section:last-child {
    border-bottom: none;
  }
  
  .cv-section-heading {
    color: rgb(32, 113, 135);
    border-bottom: 2px solid rgb(32, 113, 135);
    padding-bottom: 0.5rem;
    margin-top: 1.5rem;
    margin-bottom: 1rem;
  }
  
  .cv-entry {
    margin-bottom: 1.5rem;
  }
  
  .cv-entry h3 {
    margin-bottom: 0.25rem;
    color: #333;
  }
  
  .cv-institution {
    margin-top: 0.25rem;
    margin-bottom: 0.25rem;
  }
  
  .cv-details {
    margin-top: 0.25rem;
    color: #666;
  }
  
  .cv-details-list {
    margin-top: 0.5rem;
    margin-left: 1.5rem;
  }
  
  .cv-list {
    margin-left: 0;
    padding-left: 0;
  }
  
  .cv-projects {
    margin-bottom: 1rem;
  }
  
  .cv-project-item {
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    border-bottom: 1px solid #f2f2f2;
  }
  
  .cv-project-item:last-child {
    border-bottom: none;
  }
  
  .cv-project-item h3 {
    margin-bottom: 0.5rem;
  }
  
  /* Skills section styling */
  .skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-bottom: 1rem;
  }
  
  .skills-card {
    flex: 1 0 45%;
    min-width: 250px;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  
  .skills-card-header {
    background: linear-gradient(135deg, rgb(32, 113, 135), rgb(45, 145, 170));
    padding: 10px 15px;
  }
  
  .skills-card-header h3 {
    margin: 0;
    color: white;
    font-size: 1.1em;
  }
  
  .skills-card-content {
    padding: 12px 15px;
    background-color: #f8f9fa;
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }
  
  .skill-tag {
    display: inline-block;
    background-color: white;
    padding: 4px 10px;
    border-radius: 20px;
    font-size: 0.85em;
    border: 1px solid #e0e0e0;
  }
  
  .skill-tag-highlighted {
    background-color: rgb(32, 113, 135);
    color: white;
    border-color: rgb(32, 113, 135);
    font-weight: bold;
  }
  
  /* Interests section styling */
  .interests-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
  }
  
  .interest-category {
    flex: 1 0 30%;
    min-width: 200px;
    background-color: #f8f9fa;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  
  .interest-category h3 {
    color: rgb(32, 113, 135);
    margin-top: 0;
    margin-bottom: 0.5rem;
    border-bottom: 1px solid #e0e0e0;
    padding-bottom: 5px;
  }
  
  .interest-category p {
    margin: 0;
    line-height: 1.5;
  }
</style>
