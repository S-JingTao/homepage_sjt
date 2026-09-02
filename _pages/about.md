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

My current research interests include **Robotics**, **Physical AI**,
**Multimodal Learning**, **Autonomous Driving**.

<div style="height: 60px;"></div>

<h2>representative projects</h2>

<div class="representative-project-grid">

  <a class="representative-project-card" href="项目1链接">
    <img
      src="{{ '/assets/img/projects/robot_learning.gif' | relative_url }}"
      alt="Project 1"
    >
    <div class="representative-project-title">Project 1 Title</div>
    <div class="representative-project-description">
      A short description of Project 1.
    </div>
  </a>

  <a class="representative-project-card" href="项目2链接">
    <img
      src="{{ '/assets/img/projects/aerial_robot.gif' | relative_url }}"
      alt="Project 2"
    >
    <div class="representative-project-title">Project 2 Title</div>
    <div class="representative-project-description">
      A short description of Project 2.
    </div>
  </a>

  <a class="representative-project-card" href="项目3链接">
    <img
      src="{{ '/assets/img/projects/autonomous_driving.gif' | relative_url }}"
      alt="Project 3"
    >
    <div class="representative-project-title">Project 3 Title</div>
    <div class="representative-project-description">
      A short description of Project 3.
    </div>
  </a>

  <a class="representative-project-card" href="项目4链接">
    <img
      src="{{ '/assets/img/projects/pose.gif' | relative_url }}"
      alt="Project 4"
    >
    <div class="representative-project-title">Project 4 Title</div>
    <div class="representative-project-description">
      A short description of Project 4.
    </div>
  </a>

</div>

<style>
.representative-project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin: 20px 0 36px;
}

.representative-project-card {
  display: block;
  overflow: hidden;
  color: inherit;
  text-decoration: none;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 8px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.representative-project-card:hover {
  color: inherit;
  text-decoration: none;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.18);
}

.representative-project-card img {
  display: block;
  width: 100%;
  height: 200px;
  object-fit: fill;
  object-position: center;
  border-radius: 8px 8px 0 0;
}

.representative-project-title {
  padding: 12px 14px 4px;
  font-size: 1.05rem;
  font-weight: 600;
}

.representative-project-description {
  padding: 0 14px 14px;
  font-size: 0.9rem;
  color: #999;
}

@media (max-width: 700px) {
  .representative-project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
