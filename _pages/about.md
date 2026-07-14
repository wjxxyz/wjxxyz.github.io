---
layout: about
title: about
permalink: /
subtitle: M.S. Student in Computer Science, <a href='https://www.bjtu.edu.cn/'>Beijing Jiaotong University</a>

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Beijing, China</p>
    <p><a href="mailto:wjx15686366415@163.com">wjx15686366415@163.com</a></p>
    <p>WeChat: 15686366415</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a master's student in Computer Science and Technology at **[Beijing Jiaotong University](https://www.bjtu.edu.cn/)** (2024–2027), advised by Prof. **[Huihui Bai](https://faculty.bjtu.edu.cn/8181/)**. I received my B.Eng. in Computer Science from North China University of Technology (2020–2024), ranked 2/109, and was recommended for admission to BJTU.

My research focuses on **diffusion models**, **human motion generation**, and **video generation & editing**. I am interested in efficient, high-fidelity generation directly in the raw / pixel space without relying on a VAE, decoupling condition injection from result prediction for end-to-end diffusion optimization.

I have first- and co-authored papers at top venues (ACM MM, ICML). For more details, see my [CV](/cv/).

## Experience

**Meitu MTLab** — Computer Vision Algorithm Intern · *Sep 2025 – Jun 2026*
Trained Wan 2.1/2.2 video generation models with FSDP distributed training for video portrait, subtitle, and passerby removal. Injected conditions via channel concatenation to guide the diffusion model, and designed an independent mask-prediction head that perceives target regions without explicit mask input. Built a multi-source paired video pipeline (Blender 3D rendering + video compositing) producing ~50k long-video clips of 301 frames each.

**Academy of Military Sciences**, Information Research Center — Large-Model Algorithm Intern · *Jun 2024 – Sep 2024*
Collected, cleaned, and constructed safety corpora for large models, and fine-tuned models on the cleaned data. Deployed and served models with vLLM and Ollama. Won an award in the finals of a large-model data-safety competition.
