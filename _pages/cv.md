---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div markdown="1" class="cv-section">
## Work Experience
{: .section-heading}

### 📌 Research Assistant (Mar 2025 - Present)  
**Victoria University of Wellington**  
*Supervisors: Bing Xue, Mengjie Zhang*

### 📌 Intern at Digital & AI Team (Sep 2024 - Mar 2025)  
**Callaghan Innovation**  
- Engaged in the **GovGPT** and **PaperBoi (Science-Paper Conversational Agent) projects**.
- Enhanced large language model responses by fine-tuning the retrieval-augmented generation (RAG) component, focusing on retrieval improvements and prompt engineering.  

### 📌 Doctoral Researcher (Oct 2021 - Feb 2025)  
**Victoria University of Wellington**  
- Collaborated with **Manaaki Whenua – Landcare Research** to develop advanced AI models for segmenting individual tree crowns from aerial imagery in the Wellington region.  
- Worked with the team to assess project progress and communicated key findings through reports and presentations.  
- *Supervisors: Bing Xue, Mengjie Zhang, Jan Schindler*
</div>


<div markdown="1" class="cv-section">
## Projects
{: .section-heading}

<ul class="projects-list" style="padding-left: 40px;">
  {% for post in site.projects reversed %}
    <li>
      <a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</div>


<div markdown="1" class="cv-section">
## Skills
{: .section-heading}

-  **Computer Languages**: Advanced in Python, Java, C/C++, MATLAB.  

-  **Data Analysis**: Experienced in using Python libraries such as Pandas, NumPy, and Scipy for data analysis.  

-  **Databases**: Familiar with SQL.  

-  **Framework and Libraries**: PyTorch, TensorFlow, Matplotlib, OpenCV, Scikit-learn.  

-  **Algorithms**: Expertise in computer vision and machine learning techniques, with proficiency in deep learning, YOLO models, Transformer models, object detection tasks, and image segmentation tasks.  

-  **Softwares**: Jupyter, Visual Studio, PyCharm, Microsoft Office, Photoshop.  

-  **Repositories**: GitHub, GitLab.  

-  **Interpersonal Skills**: Team work, leadership, and consultation.  

-  **Academic and Professional Skills**: Research, presentation, teaching, and training.  
</div>


<div markdown="1" class="cv-section">
## Publications
{: .section-heading}

<ul class="publications-list" style="padding-left: 40px;">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
</div>


<div markdown="1" class="cv-section">
## Talks
{: .section-heading}

<ul class="talks-list" style="padding-left: 40px;">
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>
</div>


<div markdown="1" class="cv-section">
## Education
{: .section-heading}

### 📌 PhD in Engineering and Computer Science  
**Victoria University of Wellington** | 🎯 *Expected 2025*  

### 📌 MSc in Computer Science and Technology  
**Shandong University of Finance and Economics** | 🎯 *2021*  

### 📌 BSc in Computer Science and Technology  
**Shandong University of Finance and Economics** | 🎯 *2018*  
</div>


<div markdown="1" class="cv-section">
## Interests
{: .section-heading}

**Outdoor Activities:** Hiking 🚶, Fishing 🎣, Cycling 🚴, Swimming 🏊  

**Intellectual Hobbies:** Reading 📖, Researching 🧠  

**Sports & Fitness:** Badminton 🏸, Gym 💪  
</div>

<style>
.cv-section {
  margin-bottom: 30px;
  padding: 15px;
  background-color: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.section-heading {
  color: rgb(32, 113, 135);
  border-bottom: 2px solid rgb(32, 113, 135);
  padding-bottom: 10px;
  margin-top: 0;
}

.subsection-heading {
  color: rgb(32, 113, 135);
  border-bottom: 1px solid #e0e0e0;
  padding-bottom: 8px;
  margin-top: 0;
}

/* Projects styling */
.projects-list {
  padding-left: 0;
}

.project-item {
  margin-bottom: 15px;
  border-bottom: 1px solid #eee;
  padding-bottom: 15px;
}

.project-item:last-child {
  border-bottom: none;
}

.project-item h3 {
  margin-bottom: 5px;
}

/* Skills styling */
.skills-wrapper {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.skills-subsection {
  flex: 1 1 45%;
  min-width: 250px;
  background-color: white;
  padding: 12px;
  border-radius: 6px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.08);
}

.skills-subsection ul {
  list-style-type: none;
  padding-left: 15px;
}

.skills-subsection li {
  padding: 5px 0;
  position: relative;
}

.skills-subsection li:before {
  content: "•";
  color: rgb(32, 113, 135);
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-left: -1em;
}

/* Publications and talks lists */
.publications-list, .talks-list {
  padding-left: 0;
}

@media (max-width: 768px) {
  .skills-subsection {
    flex: 1 1 100%;
  }
}
</style>
