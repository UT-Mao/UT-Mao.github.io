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

I am currently a research scientist at Cyberagent AI Lab. I worked as a project researcher with Aizawa Lab of The University of Tokyo, Japan. 

My research interest is in Computer Vision, including controllable image generation and visual understanding. 


# News
- *2025.11*: &nbsp;🎉🎉 1 paper is accpeted by AAAI 2026****
- *2025.07*: &nbsp;🎉🎉 1 paper is accpeted by ICCV 2025 Workshop
- *2025.07*: &nbsp;🎉🎉 1 paper is accpeted by ACM MM 2025
- *2025.05*: &nbsp;🎉🎉 2 papers are accpeted by ICIP 2025
- *2025.04*: &nbsp;🎉🎉 1 paper is accpeted as oral by CVPR 2025 workshop AI4CC
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/fig_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LORE: Latent Optimization for Precise Semantic Control in Rectified Flow-based Image Editing](https://arxiv.org/pdf/2508.03144)

Liangyang Ouyang, **Jiafeng Mao**
- Analyzing the generation tendency issue in the image editing task 
- Inverted noise optimization for semantic control in RF-based image editing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/MangaDiT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MangaDiT: Reference-Guided Line Art Colorization with Hierarchical Attention in Diffusion Transformers](https://www.arxiv.org/pdf/2508.09709)

Qianru Qiu, **Jiafeng Mao**, Kento Masui, Xueting Wang
- DiT-based Manga lineart colorization with a reference colorized image
- Hierarchical Attention for Precise region matching
</div>
</div>


- [Training Data Synthesis with Difficulty Controlled Diffusion Model](https://arxiv.org/abs/2411.18109v1), Zerun Wang, **Jiafeng Mao**, Xueting Wang, Toshihiko Yamasaki. **AAAI 2026**
- [Exploring Palette based Color Guidance in Diffusion Models](), Qianru Qiu, **Jiafeng Mao**, Xueting Wang. **ACM MM 2025**
- [Task-Specific Generative Dataset Distillation with Difficulty-Guided Sampling](), Mingzhuo Li, Guang Li, **Jiafeng Mao**, Linfeng Ye, Takahiro Ogawa, Miki Haseyama. **ICCV 2025 Workshop CDEL**
- [Diversity-Driven Generative Dataset Distillation based on Diffusion Model with Self-Adaptive Memory](), Mingzhuo Li, Guang Li, **Jiafeng Mao**, Takahiro Ogawa, Miki Haseyama.  **ICIP 2025**
- [Noisy Label Refinement with Semantically Reliable Synthetic Images](), Yingxuan Li, **Jiafeng Mao**, Yusuke Matsui.  **ICIP 2025**
- [Training-Free Sketch-Guided Diffusion with Latent Optimization](https://arxiv.org/abs/2409.00313), Sandra Zhang Ding, **Jiafeng Mao**, Kiyoharu Aizawa.  **CVPR Workshop 2025**
- [Dealing with Synthetic Data Contamination in Online Continual Learning](https://arxiv.org/pdf/2411.13852), Maorong Wang, Nicolas Michel, **Jiafeng Mao** and Toshihiko Yamasaki. **NeurIPS 2024**
- [SCOMatch: Alleviating Overtrusting in Open-set Semi-supervised Learning](https://arxiv.org/pdf/2409.17512), Zerun Wang, Liuyu Xiang, Lang Huang, **Jiafeng Mao**, Ling Xiao and Toshihiko Yamasaki.**ECCV 2024**
- [Noise-Avoidance Sampling for Annotation Missing Object Detection](https://ieeexplore.ieee.org/document/10222557), **Jiafeng Mao**, Qing Yu, Irie Go and Kiyoharu Aizawa. **ICIP 2023**
- [Training-Free Location-Aware Text-to-Image Synthesis](https://arxiv.org/pdf/2304.13427), **Jiafeng Mao**, Xueting Wang.**ICIP 2023(Oral)**
- [Noisy Annotation Refinement for Object Detection](https://arxiv.org/pdf/2110.10456), **Jiafeng Mao**, Qing Yu, Yoko Yamakata and Kiyoharu Aizawa. **BMVC 2021**
- [Noisy Localization Annotation Refinement for Object Detection](https://ieeexplore.ieee.org/document/9190728), **Jiafeng Mao**, Qing Yu and Kiyoharu Aizawa. **ICIP2020(Oral)**

## arXiv Papers
- [From Obstacles to Resources: Semi-supervised Learning Faces Synthetic Data Contamination](https://arxiv.org/abs/2405.16930), Zerun Wang, **Jiafeng Mao**, Liuyu Xiang, Toshihiko Yamasaki
- [Reward Incremental Learning in Text-to-Image Generation](https://arxiv.org/abs/2411.17310), Maorong Wang, **Jiafeng Mao**, Xueting Wang, Toshihiko Yamasaki

## Domestic
- 20+ Papers in MIRU etc.


# Honors and Awards
- *2025* Reviewer for CVPR 2025, ICCV 2025, ACM MM 2025, WACV 2025, ICME 2025, MIRU 2025
- *2024* Reviewer for CVPR 2024, ECCV 2024, ACM MM 2024, MIRU 2024
- *2022* IST-RA: A Doctoral Student Special Incentives Program provided by the University of Tokyo Graduate School of Information Science and Technology.
- *2020* Kaggle Global Wheat Detection Competition Silver Medal. 
- *2020* MIRU Student Encouragement Award

