---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 About Me

Hi! My name is Omar. I am an MSc candidate in Robotics at [Mohamed bin Zayed University of Artificial Intelligence (MBZUAI)](https://mbzuai.ac.ae/), supervised by Prof. [Cesare Stefanini](https://scholar.google.com/citations?user=4ySaHDQAAAAJ&hl=en). My research focuses on **surgical robotics and robot learning**.

Before joining MBZUAI, I earned my BSc in Mechatronics Engineering from [Nile University](https://www.nu.edu.eg/), graduating with Highest Honors. Beyond research, I am passionate about robotics innovation and have participated in over 30 scientific competitions, fairs, and conferences, earning 22 national and international awards across the USA, China, South Korea, and Latvia.

# 🎓 Education

<div class="education-list">

  <!-- MBZUAI -->
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/images/education/mbzuai.png' | relative_url }}" alt="MBZUAI logo">
    </div>
    <div class="education-info">
      <div class="education-heading">
        <h3>Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), Abu Dhabi, UAE</h3>
      </div>
      <div class="education-bottom">
        <span class="education-subtitle">M.Sc. in Robotics · Full Scholarship</span>
        <span class="education-date">Aug 2025 – Present</span>
      </div>
    </div>
  </div>

  <!-- UCL -->
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/images/education/ucl.png' | relative_url }}" alt="UCL logo">
    </div>
    <div class="education-info">
      <div class="education-heading">
        <h3>University College London (UCL), London, UK</h3>
      </div>
      <div class="education-bottom">
        <span class="education-subtitle">Research Visit · Surgical Robot Vision Group</span>
        <span class="education-date">Jun – Aug 2026</span>
      </div>
    </div>
  </div>

  <!-- Nile University -->
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/images/education/nile.png' | relative_url }}" alt="Nile University logo">
    </div>
    <div class="education-info">
      <div class="education-heading">
        <h3>Nile University (NU), Giza, Egypt</h3>
      </div>
      <div class="education-bottom">
        <span class="education-subtitle">B.Sc. in Mechatronics Engineering · Full Scholarship · GPA 3.85/4.00 (Highest Honors)</span>
        <span class="education-date">Oct 2020 – Feb 2025</span>
      </div>
    </div>
  </div>

  <!-- RTU -->
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/images/education/rtu.png' | relative_url }}" alt="Riga Technical University logo">
    </div>
    <div class="education-info">
      <div class="education-heading">
        <h3>Riga Technical University (RTU), Riga, Latvia</h3>
      </div>
      <div class="education-bottom">
        <span class="education-subtitle">Semester Abroad in Mechatronics Engineering · Erasmus+ Scholarship</span>
        <span class="education-date">Jan – Jun 2024</span>
      </div>
    </div>
  </div>

</div>

# 📝 Publications

{% include publications.html %}

# 🎖 Honors and Awards

{% include honors.html %}

