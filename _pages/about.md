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
/* Section titles: short gradient accent bar */
.section-title {
  position: relative;
  padding-bottom: 10px;
  margin-top: 44px;
  margin-bottom: 22px;
  color: #1a1a2e;
  letter-spacing: 0.3px;
}
.section-title::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 46px;
  height: 3px;
  border-radius: 2px;
  background: linear-gradient(90deg, #00509e, #4a90d9);
}

/* News */
.news-list {
  max-height: 220px;
  overflow-y: auto;
  padding: 4px 10px;
  border: 1px solid #ececec;
  border-radius: 10px;
  background: #fff;
}
.news-item {
  padding: 7px 2px;
  font-size: 0.93em;
  border-bottom: 1px dashed #eee;
}
.news-item:last-child {
  border-bottom: none;
}
.news-date {
  display: inline-block;
  min-width: 86px;
  color: #00509e;
  font-weight: 600;
  font-size: 0.9em;
  margin-right: 6px;
}

/* Project cards */
.project-card {
  display: flex;
  flex-direction: row;
  margin-bottom: 22px;
  padding: 14px;
  border: 1px solid #e8e8e8;
  border-radius: 12px;
  background: #fff;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}
.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 22px rgba(0, 40, 90, 0.1);
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
  border-radius: 8px;
}
.project-info {
  flex: 1;
}
.project-info h3 {
  margin: 0 0 8px 0;
  font-size: 1em;
  line-height: 1.35;
  color: #1a1a2e;
}
.project-venue {
  display: inline-block;
  padding: 2px 10px;
  border-radius: 999px;
  background: #eaf2fb;
  color: #00509e;
  font-size: 0.78em;
  font-weight: 600;
  margin-bottom: 8px;
}
.project-authors {
  font-size: 0.8em;
  color: #555;
  margin-bottom: 10px;
}
.project-links a {
  display: inline-block;
  margin: 0 6px 4px 0;
  padding: 3px 14px;
  border: 1px solid #00509e;
  border-radius: 999px;
  color: #00509e !important;
  background: transparent;
  font-size: 0.8em;
  font-weight: 500;
  text-decoration: none;
  transition: background 0.2s ease, color 0.2s ease;
}
.project-links a:hover {
  background: #00509e;
  color: #fff !important;
}

/* Awards */
.award-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 16px;
  margin-bottom: 20px;
}
.award-card {
  text-align: center;
  padding: 10px 10px 4px 10px;
  border: 1px solid #e8e8e8;
  border-radius: 12px;
  background: #fff;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}
.award-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 22px rgba(0, 40, 90, 0.1);
}
.award-card img {
  width: 220px;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}
.award-card p {
  color: #666;
  font-size: 0.8em;
  line-height: 1.4;
  margin: 8px 0 6px 0;
  max-width: 230px;
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
  .project-img img {
    height: auto;
  }
}
</style>

I received my PhD from the **[Dyson School of Design Engineering](https://www.imperial.ac.uk/design-engineering/)** at **[Imperial College London](https://www.imperial.ac.uk)** in July 2026. My research focuses on:

- **Embodied AI** & Robot Learning
- **Robot Manipulation** & Perception
- **Deformable Object Manipulation**

I develop data‑efficient methods that bridge laboratory algorithms to real‑world robot tasks. I am supervised by [Dr Petar Kormushev](http://www.imperial.ac.uk/robot-intelligence/) and [Dr Nicolas Rojas](https://www.imperial.ac.uk/reds-lab/).

**Email:** [w.chen21@imperial.ac.uk](mailto:w.chen21@imperial.ac.uk)

---

<h2 class="section-title">News</h2>

<div class="news-list">
  <div class="news-item"><span class="news-date">[Jul 2026]</span> 🎓 Received my <strong>PhD degree</strong> from Imperial College London!</div>
  <div class="news-item"><span class="news-date">[May 2026]</span> 🎉 Successfully defended my <strong>PhD thesis</strong>!</div>
  <div class="news-item"><span class="news-date">[Mar 2026]</span> 🏆 Won the <strong>Amazon Robotics Award</strong>!</div>
  <div class="news-item"><span class="news-date">[2025]</span> Two papers accepted to <strong>IROS 2025</strong> (GraphGarment, Haptic-ACT)!</div>
  <div class="news-item"><span class="news-date">[2025]</span> One paper accepted to <strong>RA-L 2025</strong>!</div>
  <div class="news-item"><span class="news-date">[2025]</span> One paper accepted to <strong>CLAWAR 2025</strong>!</div>
  <div class="news-item"><span class="news-date">[2024]</span> Two papers accepted to <strong>RA-L 2024</strong> (TraKDis, G.O.G)!</div>
  <div class="news-item"><span class="news-date">[2024]</span> One paper accepted to <strong>ICMRE 2024</strong>!</div>
  <div class="news-item"><span class="news-date">[Oct 2023]</span> Presented at <strong>IROS 2023</strong> in Detroit!</div>
  <div class="news-item"><span class="news-date">[Jun 2023]</span> 🏆 Honorable Mention, <strong>ICRA 2023 Cloth Manipulation Challenge</strong>!</div>
  <div class="news-item"><span class="news-date">[Jun 2023]</span> One paper accepted to <strong>IROS 2023</strong>!</div>
</div>

---

<h2 class="section-title">Awards</h2>

<div class="award-row">
  <div class="award-card">
    <img src="{{ site.baseurl }}/images/amazon_award.jpg" alt="Amazon Robotics Award" loading="lazy">
    <p><strong>Amazon Robotics Award</strong><br>Mar 2026</p>
  </div>
  <div class="award-card">
    <img src="{{ site.baseurl }}/images/IEEE-cloth-award.jpg" alt="ICRA 2023 Cloth Manipulation Challenge" loading="lazy">
    <p><strong>ICRA 2023 Cloth Manipulation Challenge</strong><br>Honorable Mention &middot; Jun 2023</p>
  </div>
</div>

---

<h2 class="section-title">Research</h2>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/real_predict_demo.gif" alt="GraphGarment" loading="lazy">
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
    <img src="{{ site.baseurl }}/images/haptic_act.gif" alt="Haptic-ACT" loading="lazy">
  </div>
  <div class="project-info">
    <h3>Haptic-ACT: Bridging Human Intuition with Compliant Robotic Manipulation via Immersive VR</h3>
    <div class="project-venue">IROS 2025</div>
    <div class="project-authors">Kelin Li, Shubhan M Wagh, Nikhil Sharma, Sarthak Bhadani, <strong>Wei Chen</strong>, Chuanyu Liu, Petar Kormushev</div>
    <div class="project-links">
      <a href="https://arxiv.org/abs/2501.02248" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/haptic-act" target="_blank">Website</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/therbligs_backbone.gif" alt="Therbligs" loading="lazy">
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

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/Trakdis.gif" alt="TraKDis" loading="lazy">
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
    <img src="{{ site.baseurl }}/images/gog_demo.gif" alt="G.O.G" loading="lazy">
  </div>
  <div class="project-info">
    <h3>G.O.G: A Versatile Gripper-On-Gripper Design for Bimanual Cloth Manipulation</h3>
    <div class="project-venue">IEEE RA-L 2024</div>
    <div class="project-authors">Dongmyoung Lee*, <strong>Wei Chen*</strong>, Xiaoshuai Chen, Nicolas Rojas (* equal contribution)</div>
    <div class="project-links">
      <a href="https://arxiv.org/pdf/2401.10702.pdf" target="_blank">Paper</a>
      <a href="https://sites.google.com/view/gripperongripper" target="_blank">Website</a>
    </div>
  </div>
</div>

<div class="project-card">
  <div class="project-img">
    <img src="{{ site.baseurl }}/images/ICMRE.jpg" alt="Synthetic Data" loading="lazy">
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
    <img src="{{ site.baseurl }}/images/garment_hang.gif" alt="Garment Hanging" loading="lazy">
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

---

<div style="text-align: center; margin-top: 30px; padding: 20px;">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Rudy112.weichen.github.io" alt="visitors">
</div>
