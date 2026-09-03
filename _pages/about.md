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

<h2>representative research</h2>

<div class="representative-project-grid">

  <div class="representative-project-card">

  <a class="representative-project-main" href="项目1链接">
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
    >
      ICRA 2026
    </a>
    ·
    <a
      href="论文2链接"
      target="_blank"
      rel="noopener noreferrer"
    >
      TII 2026
    </a>
  </div>

</div>
      
</div>
    
  </a>

  <a class="representative-project-card" href="项目2链接">
    <img
      src="{{ '/assets/img/projects/aerial_robot.gif' | relative_url }}"
      alt="Project 2"
    >
    <div class="representative-project-title">Air-Ground Robotic Manipulation</div>
    <div class="representative-project-description">
      Develop collaborative air-ground robotic manipulation systems that integrate aerial perception, ground-based operation, and multimodal sensing to perform complex tasks in dynamic and unstructured environments.
    </div>
  </a>

  <a class="representative-project-card" href="项目3链接">
    <img
      src="{{ '/assets/img/projects/autonomous_driving.gif' | relative_url }}"
      alt="Project 3"
    >
    <div class="representative-project-title">End-to-End Autonomous Driving Agents</div>
    <div class="representative-project-description">
      Develop autonomous driving agents that integrate vision, LiDAR, language, and vehicle-state information for comprehensive scene understanding, reliable decision-making, and safe trajectory planning in complex driving environments.
    </div>
  </a>

  <a class="representative-project-card" href="项目4链接">
    <img
      src="{{ '/assets/img/projects/pose.gif' | relative_url }}"
      alt="Project 4"
    >
    <div class="representative-project-title">Pose Tracking & Shape Reconstruction</div>
    <div class="representative-project-description">
      Develop categorical pose tracking and shape reconstruction methods to provide accurate spatial understanding and dynamic object representations for perception-driven robot learning and reliable manipulation in complex real-world environments.
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
  height: 250px;
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

.representative-project-main {
  display: block;
  color: inherit;
  text-decoration: none;
}

.representative-project-main:hover {
  color: inherit;
  text-decoration: none;
}

.representative-project-paper {
  padding: 0 14px 14px;
  font-size: 0.9rem;
  color: #b39ddb;
}

.representative-project-paper a {
  color: inherit;
  font-weight: 500;
  text-decoration: none;
}

.representative-project-paper a:hover {
  color: #d1c4e9;
  text-decoration: underline;
}

@media (max-width: 700px) {
  .representative-project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
