---
layout: about
title: About
permalink: /
subtitle: Postdoctoral/Research Fellow, NUS

profile:
  align: right
  image: sjt_new.png
  image_circular: false
  more_info: 

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I am currently a Research Fellow in
[Show Lab](https://sites.google.com/view/showlab) at the Electrical and Computer Engineering,
National University of Singapore (NUS),
working with
[Prof. Mike Shou Zheng](https://sites.google.com/view/showlab).
 Prior to this, I spent a wonderful year as a Research Fellow at Social Robotics Lab (NUS), working with [Prof. Sam Ge Shuzhi (IEEE Fellow)](https://cde.nus.edu.sg/ece/staff/ge-shuzhi-sam/).

I received my Ph.D. degree from
Hunan University in 2024, where I was
affiliated with the National Engineering Research Centre for Robot
Visual Perception and Control [(机器人视觉感知与控制技术国家工程研究中心)](https://robot.hnu.edu.cn/index.htm),
under the supervision of
[Prof. Yaonan Wang (王耀南)](https://robotics.hnu.edu.cn/info/1176/3098.htm). I also received my bachelor's
and master's degrees from Hunan University.

My current research interests include **robotics**, **physical AI**,
**multimodal learning**, **autonomous driving**.

<h2>Representative Projects</h2>

<div class="Representative Project-grid">

  <a class="Representative Project-card" href="">
    <img
      src="{{ '/assets/img/projects/project1.gif' | relative_url }}"
      alt="Project 1"
    >
    <div class="selected-project-title">Project 1 Title</div>
    <div class="selected-project-description">
      A short description of Project 1.
    </div>
  </a>

  <a class="Representative Project" href="">
    <img
      src="{{ '/assets/img/projects/project2.gif' | relative_url }}"
      alt="Project 2"
    >
    <div class="selected-project-title">Project 2 Title</div>
    <div class="selected-project-description">
      A short description of Project 2.
    </div>
  </a>

  <a class="Representative Project-card" href="">
    <img
      src="{{ '/assets/img/projects/project3.gif' | relative_url }}"
      alt="Project 3"
    >
    <div class="selected-project-title">Project 3 Title</div>
    <div class="selected-project-description">
      A short description of Project 3.
    </div>
  </a>

  <a class="Representative Project-card" href="">
    <img
      src="{{ '/assets/img/projects/project4.gif' | relative_url }}"
      alt="Project 4"
    >
    <div class="selected-project-title">Project 4 Title</div>
    <div class="selected-project-description">
      A short description of Project 4.
    </div>
  </a>

</div>

<style>
.selected-project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin: 20px 0 36px;
}

.Representative Project-card {
  display: block;
  overflow: hidden;
  color: inherit;
  text-decoration: none;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 8px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.Representative Project-card:hover {
  color: inherit;
  text-decoration: none;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.18);
}

.Representative Project-card img {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  object-fit: cover;
}

.Representative Project-title {
  padding: 12px 14px 4px;
  font-size: 1.05rem;
  font-weight: 600;
}

.Representative Project-description {
  padding: 0 14px 14px;
  font-size: 0.9rem;
  color: #999;
}

@media (max-width: 700px) {
  .Representative Project-grid {
    grid-template-columns: 1fr;
  }
}
<\style>
