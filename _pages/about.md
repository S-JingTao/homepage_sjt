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
 Prior to this, I spent a wonderful year as a Research Fellow at Social Robotics Lab (NUS), working with [Prof. Sam Ge Shuzhi](https://cde.nus.edu.sg/ece/staff/ge-shuzhi-sam/). I previously worked as a AI Research Scientist at Huawei Co., Ltd. Wuhan Research Institute in China.

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

<h2>Representative Projects</h2>

<div class="representative-project-grid">

  
  <div class="representative-project-card">

  <a class="representative-project-main" href="项目1主页链接">
      <img
        src="{{ '/assets/img/projects/robot_learning.gif' | relative_url }}"
        alt="Multimodal Generalist Robotic Agents"
      >

  <div class="representative-project-title">
        Multimodal Generalist Robotic Agents
      </div>
    </a>

  <div class="representative-project-description">
      Develop generalist robot policies that integrate multimodal states,
      including vision, language, touch, and robot control, learn from
      large-scale human videos, and perform diverse real-world tasks with
      minimal robot-specific demonstrations.
    </div>

  <div class="representative-project-paper">
      <strong>Papers:</strong>
      <a
        href="https://arxiv.org/abs/2602.12532"
        target="_blank"
        rel="noopener noreferrer"
      >ICRA 2026</a>
      ·
      <a
        href="论文2链接"
        target="_blank"
        rel="noopener noreferrer"
      >TII 2026</a>
    </div>

  </div>


  <!-- Project 2 -->
  <div class="representative-project-card">

  <a class="representative-project-main" href="项目2主页链接">
      <img
        src="{{ '/assets/img/projects/aerial_robot.gif' | relative_url }}"
        alt="Air-Ground Robotic Manipulation"
      >

  <div class="representative-project-title">
        Air-Ground Robotic Manipulation
      </div>
    </a>

<div class="representative-project-description">
      Develop collaborative air-ground robotic manipulation systems that
      integrate aerial perception, ground-based operation, and multimodal
      sensing to perform complex tasks in dynamic and unstructured environments.
    </div>

<div class="representative-project-paper">
      <strong>Papers:</strong>
      <a
        href="论文1链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 1</a>
      ·
      <a
        href="论文2链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 2</a>
    </div>

  </div>


  <!-- Project 3 -->
  <div class="representative-project-card">

  <a class="representative-project-main" href="项目3主页链接">
      <img
        src="{{ '/assets/img/projects/autonomous_driving.gif' | relative_url }}"
        alt="Multimodal Autonomous Driving Agents"
      >

  <div class="representative-project-title">
        Multimodal Autonomous Driving Agents
      </div>
    </a>

  <div class="representative-project-description">
      Develop autonomous driving agents that integrate vision, LiDAR,
      language, and vehicle-state information for comprehensive scene
      understanding, reliable decision-making, and safe trajectory planning
      in complex driving environments.
    </div>

  <div class="representative-project-paper">
      <strong>Papers:</strong>
      <a
        href="论文1链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 1</a>
      ·
      <a
        href="论文2链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 2</a>
    </div>

  </div>


  <!-- Project 4 -->
  <div class="representative-project-card">

  <a class="representative-project-main" href="项目4主页链接">
      <img
        src="{{ '/assets/img/projects/pose.gif' | relative_url }}"
        alt="Pose Tracking and Shape Reconstruction"
      >

  <div class="representative-project-title">
        Pose Tracking &amp; Shape Reconstruction
      </div>
    </a>

  <div class="representative-project-description">
      Develop robust pose tracking and shape reconstruction methods to provide
      accurate spatial understanding and dynamic object representations for
      perception-driven robot learning and reliable manipulation in complex
      real-world environments.
    </div>

  <div class="representative-project-paper">
      <strong>Papers:</strong>
      <a
        href="论文1链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 1</a>
      ·
      <a
        href="论文2链接"
        target="_blank"
        rel="noopener noreferrer"
      >Paper 2</a>
    </div>

  </div>

</div>

<style>
.representative-project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
  margin: 20px 0 36px;
}

.representative-project-card {
  display: flex;
  flex-direction: column;
  overflow: hidden;
  color: inherit;
  border: 1px solid rgba(128, 128, 128, 0.25);
  border-radius: 8px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.representative-project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.18);
}

.representative-project-main {
  display: block;
  color: inherit;
  text-decoration: none;
}

.representative-project-main:hover {
  color: inherit;
  text-decoration: none;
}

.representative-project-card img {
  display: block;
  width: 100%;
  height: 260px;
  object-fit: fill;
  border-radius: 8px 8px 0 0;
}

.representative-project-title {
  padding: 12px 14px 4px;
  font-size: 1.05rem;
  font-weight: 600;
}

.representative-project-description {
  flex-grow: 1;
  padding: 4px 14px 12px;
  font-size: 0.9rem;
  color: #999;
}

.representative-project-paper {
  margin-top: auto;
  padding: 4px 14px 16px;
  font-size: 0.9rem;
  color: #b39ddb;
}

.representative-project-paper {
  margin-top: auto;
  padding: 0 14px 14px;
  font-size: 0.9rem;
}

.representative-project-paper strong {
  color: var(--global-theme-color);
}

.representative-project-paper a {
  color: var(--global-theme-color);
  font-weight: 500;
  text-decoration: none;
}

.representative-project-paper a:hover {
  color: var(--global-hover-color);
  text-decoration: underline;
}

@media (max-width: 700px) {
  .representative-project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
