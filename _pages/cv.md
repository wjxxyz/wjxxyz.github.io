---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

个人简介
======
计算机科学与技术硕士研究生，研究方向为扩散模型、人体运动生成与视频生成编辑，具备顶会论文研究及工业算法实习经历。

Education
======
* 北京交通大学，计算机科学与技术，硕士研究生，2024.9-2027.6
  * 北京交通大学一等奖学金、校三好学生、校优秀团员
* 北方工业大学，计算机科学与技术，工学学士，2020.9-2024.6
  * 排名2/109（前2%），国家励志奖学金、一等奖学金、优秀毕业生，推免至北京交通大学

Work experience
======
* 2025.9-2026.6：计算机视觉算法实习生
  * 美图 MTLAB
  * 主要内容：使用FSDP分布式训练Wan 2.1/2.2视频生成模型，面向视频人像、字幕与路人消除开展模型训练和方案迭代。采用通道拼接注入条件信息，引导扩散模型消除目标；设计独立掩码预测头，在无显式掩码输入时感知目标区域，预测消除结果视频；探索同步预测消除结果视频与精细Matting视频方案。设计多源配对视频生成方案，结合Blender三维渲染与视频贴图合成，构建约5万组、每组301帧的长视频训练数据。

* 2024.6-2024.9：大模型算法工程师实习生
  * 中国军事科学院 \| 信息研究中心
  * 主要内容：负责大模型安全语料的网页采集、清洗与数据集构建，基于清洗数据完成模型微调；使用vLLM与Ollama进行模型部署与调用，参与大模型数据安全竞赛并在决赛中获奖。

Research experience
======
* 2026.1-至今：raw-space动作序列扩散生成研究
  * 北京交通大学
  * 得益于近期像素空间图像生成模型领域的飞速发展，以及业界越来越强的对超高像素图像生成的需求，研究如何在不借助VAE的情况下做到又好又快生成。解耦条件注入与结果预测，减少模型主干token算力要求，实现端到端扩散模型优化，取得了较为领先的生成效果。

* 2024.4-2025.6：Text-to-Motion离散扩散研究
  * 北京交通大学
  * 基于VQ-VAE构建动作序列离散表示，研究VQ-Diffusion在文本驱动动作生成中的性能优化与可编辑生成能力。将离散扩散采样压缩至10步，在提高生成速度的同时取得0.051的Motion FID。

Skills
======
* 编程语言
  * Python
  * C/C++
* 生成模型与算法
  * Diffusion
  * Flow Matching
  * DMD
  * VQ-VAE
* 视觉与工程工具
  * PyTorch, FSDP, OpenCV
  * Wan 2.1/2.2, Blender
  * Linux, Git, vLLM, Ollama

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Awards
======
* 蓝桥杯编程大赛，全国三等奖
* 天梯赛团体赛，全国三等奖
