---
permalink: /
title: "Wei Chen"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* Section styling */
.section-title {
  border-bottom: 2px solid #4a90d9;
  padding-bottom: 8px;
  margin-top: 40px;
  margin-bottom: 20px;
  color: #333;
}

/* News styling */
.news-list {
  max-height: 200px;
  overflow-y: auto;
  padding: 10px;
  background: #f9f9f9;
  border-radius: 6px;
}
.news-item {
  margin-bottom: 8px;
  font-size: 0.95em;
}
.news-date {
  color: #4a90d9;
  font-weight: bold;
  margin-right: 10px;
}

/* Project cards */
.project-card {
  display: flex;
  flex-direction: row;
  margin-bottom: 20px;
  padding: 12px;
  border: 1px solid #e1e1e1;
  border-radius: 8px;
  background: #fafafa;
  transition: box-shadow 0.2s;
}
.project-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
}
.project-img {
  flex: 0 0 240px;
  max-width: 240px;
  margin-right: 18px;
}
.project-img img {
  width: 100%;
  height: 140px;
  object-fit: cover;
  border-radius: 6px;
}
.project-info {
  flex: 1;
}
.project-info h3 {
  margin: 0 0 6px 0;
  font-size: 1em;
  line-height: 1.3;
}
.project-venue {
  color: #e74c3c;
  font-size: 0.85em;
  font-weight: 500;
  margin-bottom: 6px;
}
.project-authors {
  font-size: 0.8em;
  color: #555;
  margin-bottom: 8px;
}
.project-links a {
  display: inline-block;
  margin-right: 8px;
  padding: 3px 8px;
  background: #4a90d9;
  color: white !important;
  border-radius: 4px;
  font-size: 0.8em;
  text-decoration: none;
}
.project-links a:hover {
  background: #357abd;
}

/* Education/Experience */
.exp-item {
  display: flex;
  margin-bottom: 15px;
  padding-bottom: 15px;
  border-bottom: 1px dashed #ddd;
}
.exp-item:last-child {
  border-bottom: none;
}
.exp-year {
  flex: 0 0 100px;
  font-weight: bold;
  color: #4a90d9;
  font-size: 0.9em;
}
.exp-content {
  flex: 1;
}
.exp-content strong {
  color: #333;
}
.exp-content .subtitle {
  color: #666;
  font-size: 0.9em;
}

/* Responsive */
@media (max-width: 600px) {
  .project-card {
    flex-direction: column;
  }
  .project-img {
    max-width: 100%;
    margin-right: 0;
    margin-bottom: 12px;
  }
  .exp-item {
    flex-direction: column;
  }
  .exp-year {
    margin-bottom: 5px;
  }
}
</style>

I am a final‑year PhD candidate in the **[Dyson School of Design Engineering](https://www.imperial.ac.uk/design-engineering/)** at **[Imperial College London](https://www.imperial.ac.uk)**. My research focuses on:

- **Robot Manipulation** & Perception for Grasping
- **Learning‑based Control** for Deformable Objects
- **Cloth/Garment Manipulation**

I develop data‑efficient methods that bridge laboratory algorithms to real‑world robot tasks. I am supervised by [Dr Petar Kormushev](http://www.imperial.ac.uk/robot-intelligence/) and [Dr Nicolas Rojas](https://www.imperial.ac.uk/reds-lab/). I am also a **Research Intern at Huawei UK R&D**.

---

<h2 class="section-title">News</h2>

<div class="news-list">
  <div class="news-item"><span class="news-date">[2025]</span> Two papers accepted to <strong>IROS 2025</strong> (GraphGarment, Haptic-ACT)!</div>
  <div class="news-item"><span class="news-date">[2025]</span> One paper accepted to <strong>RA-L 2025</strong>!</div>
  <div class="news-item"><span class="news-date">[2025]</span> One paper accepted to <strong>CLAWAR 2025</strong>!</div>
  <div class="news-item"><span class="news-date">[2024]</span> Two papers accepted to <strong>RA-L 2024</strong> (TraKDis, G.O.G)!</div>
  <div class="news-item"><span class="news-date">[2024]</span> One paper accepted to <strong>ICMRE 2024</strong>!</div>
  <div class="news-item"><span class="news-date">[Oct 2023]</span> Presented at <strong>IROS 2023</strong> in Detroit!</div>
  <div class="news-item"><span class="news-date">[Jun 2023]</span> One paper accepted to <strong>IROS 2023</strong>!</div>
</div>

---

<h2 class="section-title">Research</h2>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/real_predict_demo.gif" alt="GraphGarment">
  </div>
  <div class="project-info">
    <h3>GraphGarment: Learning Garment Dynamics for Bimanual Cloth Manipulation Tasks</h3>
    <div class="project-venue">IROS 2025</div>
    <div class="project-authors"><strong>Wei Chen</strong>, Kelin Li, Dongmyoung Lee, Xiaoshuai Chen, Rui Zong, Petar Kormushev</div>
    <div class="project-links">
      <a href="https://arxiv.org/pdf/2503.05817" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/graphgarment" target="_blank">Website</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/gog_demo.gif" alt="G.O.G">
  </div>
  <div class="project-info">
    <h3>G.O.G: A Versatile Gripper-On-Gripper Design for Bimanual Cloth Manipulation</h3>
    <div class="project-venue">IEEE RA-L 2024</div>
    <div class="project-authors">Dongmyoung Lee*, <strong>Wei Chen*</strong>, Xiaoshuai Chen, Nicolas Rojas</div>
    <div class="project-links">
      <a href="https://arxiv.org/pdf/2401.10702.pdf" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/gripperongripper" target="_blank">Website</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/Trakdis.gif" alt="TraKDis">
  </div>
  <div class="project-info">
    <h3>TraKDis: Transformer-based Knowledge Distillation for Visual Reinforcement Learning</h3>
    <div class="project-venue">IEEE RA-L 2024</div>
    <div class="project-authors"><strong>Wei Chen</strong>, Nicolas Rojas</div>
    <div class="project-links">
      <a href="https://arxiv.org/abs/2401.13362" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/trakdis" target="_blank">Website</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/garment_hang.gif" alt="Garment Hanging">
  </div>
  <div class="project-info">
    <h3>Learning to Grasp Clothing Structural Regions for Garment Manipulation Tasks</h3>
    <div class="project-venue">IROS 2023</div>
    <div class="project-authors"><strong>Wei Chen</strong>, Dongmyoung Lee, Digby Chappell, Nicolas Rojas</div>
    <div class="project-links">
      <a href="https://arxiv.org/pdf/2306.14553.pdf" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/garment-hanging" target="_blank">Website</a>
      <a href="https://www.youtube.com/watch?v=fEmlbfU8yss" target="_blank">Video</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/ICMRE.jpg" alt="Synthetic Data">
  </div>
  <div class="project-info">
    <h3>Synthetic Data Enables Faster Annotation and Robust Segmentation for Multi-Object Grasping</h3>
    <div class="project-venue">ICMRE 2024</div>
    <div class="project-authors">Dongmyoung Lee, <strong>Wei Chen</strong>, Nicolas Rojas</div>
    <div class="project-links">
      <a href="https://arxiv.org/pdf/2401.13405.pdf" target="_blank">Paper</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/therbligs_backbone.gif" alt="Therbligs">
  </div>
  <div class="project-info">
    <h3>A Backbone for Long-Horizon Robot Task Understanding</h3>
    <div class="project-venue">IEEE RA-L 2025</div>
    <div class="project-authors">Xiaoshuai Chen, <strong>Wei Chen</strong>, Dongmyoung Lee, Yukun Ge, Nicolas Rojas, Petar Kormushev</div>
    <div class="project-links">
      <a href="https://ieeexplore.ieee.org/document/10820869" target="_blank">Paper</a>
    </div>
  </div>
</div>

---

<div style="text-align: center; margin-top: 30px; padding: 20px;">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Rudy112.weichen.github.io" alt="visitors">
</div>
