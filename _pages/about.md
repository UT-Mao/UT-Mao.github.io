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

I am currently a research scientist at Cyberagent AI Lab, and a project researcher with The University of Tokyo, Japan. I am a member of Aizawa Labratory and working with Prof. Kiyoharu Aizawa. 

My research interest is in Computer Vision, including Image Generation, Visual Understanding and Training Data Synthesis. 


# News
- *2024.07*: &nbsp;🎉🎉 2 papers are accpeted by ECCV 2024

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/Lottery.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Lottery Ticket Hypothesis in Denoising: Towards Semantic-Driven Initialization](https://ut-mao.github.io/noise.github.io/)

**Jiafeng Mao**, Xueting Wang, Kiyoharu Aizawa

- Collecting noise pixel blocks to construct initial noise according to specified layout.
- Comfirming versatility of noise blocks over prompts and images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/swap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Guided Image Synthesis via Initial Image Editing in Diffusion Model](https://ut-mao.github.io/swap.github.io/)

**Jiafeng Mao**, Xueting Wang, Kiyoharu Aizawa

- Analyzing the generation tendency of intial noise 
- initial noise manipulation for generated image repainting and layout-to-image generation
</div>
</div>

- [Dealing with Synthetic Data Contamination in Online Continual Learning](https://arxiv.org/pdf/2411.13852), Maorong Wang, Nicolas Michel, **Jiafeng Mao** and Toshihiko Yamasaki. **NeurIPS 2024**
- [SCOMatch: Alleviating Overtrusting in Open-set Semi-supervised Learning](https://arxiv.org/pdf/2409.17512), Zerun Wang, Liuyu Xiang, Lang Huang, **Jiafeng Mao**, Ling Xiao and Toshihiko Yamasaki.**ECCV 2024**
- [Noise-Avoidance Sampling for Annotation Missing Object Detection](https://ieeexplore.ieee.org/document/10222557), **Jiafeng Mao**, Qing Yu, Irie Go and Kiyoharu Aizawa. **ICIP 2023**
- [Training-Free Location-Aware Text-to-Image Synthesis](https://arxiv.org/pdf/2304.13427), **Jiafeng Mao**, Xueting Wang.**ICIP 2023(Oral)**
- [Noisy Annotation Refinement for Object Detection](https://arxiv.org/pdf/2110.10456), **Jiafeng Mao**, Qing Yu, Yoko Yamakata and Kiyoharu Aizawa. **BMVC 2021**
- [Noisy Localization Annotation Refinement for Object Detection](https://ieeexplore.ieee.org/document/9190728), **Jiafeng Mao**, Qing Yu and Kiyoharu Aizawa. **ICIP2020(Oral)**


# Honors and Awards
- *2025* Reviewer for CVPR 2025, ICCV 2025, ACM MM 2025, ICME 2025, MIRU 2025
- *2024* Reviewer for CVPR 2024, ECCV 2024, ACM MM 2024, WACV 2024, MIRU 2024
- *2022* IST-RA: A Doctoral Student Special Incentives Program provided by the University of Tokyo Graduate School of Information Science and Technology.
- *2020* Kaggle Global Wheat Detection Competition Silver Medal. 
- *2020* MIRU Student Encouragement Award

