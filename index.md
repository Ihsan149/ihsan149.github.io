---
layout: default
title: Home
---

<div class="section intro reveal">
    <h2 class="gradient-text">Biography</h2>

    <p>I am a Research Fellow at the Camera Culture Group (CCG), Daegu Gyeongbuk Institute of Science and Technology (DGIST), working with Prof. <a href="https://sites.google.com/view/ccg-dgist/people/team-leader" target="_blank">Hyunki Lee</a>. Previously, I worked at the Medical Imaging and Signal Processing Laboratory (MISPL) at DGIST under the supervision of Prof. <a href="[https://scholar.google.com/citations?user=M9u8pFEAAAAJ](https://sites.google.com/view/mispl/members/professor)" target="_blank">Sang Hyun Park</a>.</p>

    <p>I received my Ph.D. in Robotics and Mechatronics Engineering from DGIST, South Korea, in 2023, M.S. degree in Computer Science from Chonbuk National University, South Korea, in 2017, and B.S. degree in Computer Science from Abdul Wali Khan University, Pakistan, in 2014.</p>

    <p>My research focuses on developing robust AI-based methods for medical imaging, particularly in video domain adaptation, visual-language representation learning, and generative AI techniques. I aim to bridge the gap between AI and healthcare, particularly in the context of tumor detection and characterization, to pave the way for more personalized medical approaches.</p>

    <a href="https://scholar.google.com/citations?user=eod9uX0AAAAJ&hl=en" target="_blank">Google Scholar Profile</a>
</div>

<div class="section highlights">
    <h2 class="gradient-text">Research Highlights</h2>
    <div class="highlight-grid">
        <div class="highlight-card">
            <h3>Medical Image Analysis</h3>
            <p>Developing advanced algorithms for medical image processing, segmentation, and classification.</p>
        </div>
        <div class="highlight-card">
            <h3>Domain Adaptation</h3>
            <p>Innovation in learning from limited data samples through novel neural network architectures.</p>
        </div>
        <div class="highlight-card">
            <h3>Visual-Language Representation</h3>
            <p>Exploring the intersection of vision and language for medical image analysis and computer vision.</p>
        </div>
    </div>
</div>

<div class="section news">
    <h2 class="gradient-text">Latest News</h2>
    {% for post in site.posts limit:3 %}
    <div class="news-item">
        <span class="news-date">{{ post.date | date: "%B %d, %Y" }}</span>
        <h4>{{ post.title }}</h4>
          {% if post.description %}
            <p>{{ post.description}}</p>
          {% endif %}
    </div>
    {% endfor %}
</div>
