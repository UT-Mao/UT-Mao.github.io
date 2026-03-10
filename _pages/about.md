---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="tab-content" id="tab-about-me" markdown="1">

<section class="hero-profile">
  <div class="hero-avatar">
    <img src="{{ site.author.avatar }}" alt="{{ site.author.name }}">
  </div>
  <h1 class="hero-name">{{ site.author.name }}</h1>
  <h2 class="hero-bio">{{ site.author.bio }}</h2>
  <ul class="hero-social">
    {% if site.author.email %}<li><a href="mailto:{{ site.author.email }}"><i class="fas fa-fw fa-envelope"></i></a></li>{% endif %}
    {% if site.author.github %}<li><a href="https://github.com/{{ site.author.github }}"><i class="fab fa-fw fa-github"></i></a></li>{% endif %}
    {% if site.author.googlescholar %}<li><a href="{{ site.author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i></a></li>{% endif %}
    {% if site.author.linkedin %}<li><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-fw fa-linkedin"></i></a></li>{% endif %}
    {% if site.author.twitter %}<li><a href="https://twitter.com/{{ site.author.twitter }}"><i class="fab fa-fw fa-twitter"></i></a></li>{% endif %}
    {% if site.author.cv %}<li><a href="{{ site.author.cv }}" target="_blank"><i class="fas fa-fw fa-file-pdf"></i></a></li>{% endif %}
  </ul>
</section>

# About Me

I am currently a research scientist at Cyberagent AI Lab. I worked as a project researcher with Aizawa Lab of The University of Tokyo, Japan.

My research interest is in Computer Vision, including controllable image generation and visual understanding.

# News
- *2026.02*: &nbsp; 1 paper is accepted by CVPR 2026
- *2025.11*: &nbsp; 1 paper is accepted by AAAI 2026
- *2025.07*: &nbsp; 1 paper is accepted by ICCV 2025 Workshop
- *2025.07*: &nbsp; 1 paper is accepted by ACM MM 2025
- *2025.05*: &nbsp; 2 papers are accepted by ICIP 2025

# Featured Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/MangaMatch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Region-Wise Correspondence Prediction between Manga Line Art Images](https://arxiv.org/abs/2509.09501)

Yingxuan Li, **Jiafeng Mao**, Qianru Qiu, Yusuke Matsui
- Transformer-based Manga lineart region matching
- Pseudo & Noisy Label learning
</div>
</div>

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

</div>

<div class="tab-content" id="tab-publications" style="display:none;" markdown="1">

# Publications

<h2 class="pub-section-title">Conference</h2>
<ol class="pub-ol" reversed>
<li>Yingxuan Li, <strong>Jiafeng Mao</strong>, Qianru Qiu, Yusuke Matsui.<br>
<strong>Region-Wise Correspondence Prediction between Manga Line Art Images</strong><br>
CVPR 2026. [<a href="https://arxiv.org/abs/2509.09501">paper</a>]</li>
<li>Zerun Wang, <strong>Jiafeng Mao</strong>, Xueting Wang, Toshihiko Yamasaki.<br>
<strong>Training Data Synthesis with Difficulty Controlled Diffusion Model</strong><br>
AAAI 2026. [<a href="https://arxiv.org/abs/2411.18109v1">paper</a>]</li>
<li>Qianru Qiu, <strong>Jiafeng Mao</strong>, Xueting Wang.<br>
<strong>Exploring Palette based Color Guidance in Diffusion Models</strong><br>
ACM MM 2025.</li>
<li>Mingzhuo Li, Guang Li, <strong>Jiafeng Mao</strong>, Linfeng Ye, Takahiro Ogawa, Miki Haseyama.<br>
<strong>Task-Specific Generative Dataset Distillation with Difficulty-Guided Sampling</strong><br>
ICCV 2025 Workshop CDEL.</li>
<li>Mingzhuo Li, Guang Li, <strong>Jiafeng Mao</strong>, Takahiro Ogawa, Miki Haseyama.<br>
<strong>Diversity-Driven Generative Dataset Distillation based on Diffusion Model with Self-Adaptive Memory</strong><br>
ICIP 2025.</li>
<li>Yingxuan Li, <strong>Jiafeng Mao</strong>, Yusuke Matsui.<br>
<strong>Noisy Label Refinement with Semantically Reliable Synthetic Images</strong><br>
ICIP 2025.</li>
<li>Sandra Zhang Ding, <strong>Jiafeng Mao</strong>, Kiyoharu Aizawa.<br>
<strong>Training-Free Sketch-Guided Diffusion with Latent Optimization</strong><br>
CVPR Workshop 2025. [<a href="https://arxiv.org/abs/2409.00313">paper</a>]</li>
<li>Maorong Wang, Nicolas Michel, <strong>Jiafeng Mao</strong>, Toshihiko Yamasaki.<br>
<strong>Dealing with Synthetic Data Contamination in Online Continual Learning</strong><br>
NeurIPS 2024. [<a href="https://arxiv.org/pdf/2411.13852">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Xueting Wang, Kiyoharu Aizawa.<br>
<strong>The Lottery Ticket Hypothesis in Denoising: Towards Semantic-Driven Initialization</strong><br>
ECCV 2024. [<a href="https://ut-mao.github.io/noise.github.io/">paper</a>]</li>
<li>Zerun Wang, Liuyu Xiang, Lang Huang, <strong>Jiafeng Mao</strong>, Ling Xiao, Toshihiko Yamasaki.<br>
<strong>SCOMatch: Alleviating Overtrusting in Open-set Semi-supervised Learning</strong><br>
ECCV 2024. [<a href="https://arxiv.org/pdf/2409.17512">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Xueting Wang, Kiyoharu Aizawa.<br>
<strong>Guided Image Synthesis via Initial Image Editing in Diffusion Model</strong><br>
ACM MM 2023. [<a href="https://ut-mao.github.io/swap.github.io/">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Qing Yu, Irie Go, Kiyoharu Aizawa.<br>
<strong>Noise-Avoidance Sampling for Annotation Missing Object Detection</strong><br>
ICIP 2023. [<a href="https://ieeexplore.ieee.org/document/10222557">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Xueting Wang.<br>
<strong>Training-Free Location-Aware Text-to-Image Synthesis</strong><br>
ICIP 2023 (Oral). [<a href="https://arxiv.org/pdf/2304.13427">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Qing Yu, Yoko Yamakata, Kiyoharu Aizawa.<br>
<strong>Noisy Annotation Refinement for Object Detection</strong><br>
BMVC 2021. [<a href="https://arxiv.org/pdf/2110.10456">paper</a>]</li>
<li><strong>Jiafeng Mao</strong>, Qing Yu, Kiyoharu Aizawa.<br>
<strong>Noisy Localization Annotation Refinement for Object Detection</strong><br>
ICIP 2020 (Oral). [<a href="https://ieeexplore.ieee.org/document/9190728">paper</a>]</li>
</ol>

<h2 class="pub-section-title">Preprints</h2>
<ol class="pub-ol" reversed>
<li>Liangyang Ouyang, <strong>Jiafeng Mao</strong>.<br>
<strong>LORE: Latent Optimization for Precise Semantic Control in Rectified Flow-based Image Editing</strong><br>
[<a href="https://arxiv.org/pdf/2508.03144">arXiv</a>]</li>
<li>Qianru Qiu, <strong>Jiafeng Mao</strong>, Kento Masui, Xueting Wang.<br>
<strong>MangaDiT: Reference-Guided Line Art Colorization with Hierarchical Attention in Diffusion Transformers</strong><br>
[<a href="https://www.arxiv.org/pdf/2508.09709">arXiv</a>]</li>
<li>Zerun Wang, <strong>Jiafeng Mao</strong>, Liuyu Xiang, Toshihiko Yamasaki.<br>
<strong>From Obstacles to Resources: Semi-supervised Learning Faces Synthetic Data Contamination</strong><br>
[<a href="https://arxiv.org/abs/2405.16930">arXiv</a>]</li>
<li>Maorong Wang, <strong>Jiafeng Mao</strong>, Xueting Wang, Toshihiko Yamasaki.<br>
<strong>Reward Incremental Learning in Text-to-Image Generation</strong><br>
[<a href="https://arxiv.org/abs/2411.17310">arXiv</a>]</li>
</ol>

<h2 class="pub-section-title">Domestic</h2>

20+ Papers in MIRU etc.

</div>

<div class="tab-content" id="tab-honors-and-awards" style="display:none;" markdown="1">

# Honors and Awards
- *2025* Reviewer for CVPR 2025, ICCV 2025, ACM MM 2025, WACV 2025, ICME 2025, MIRU 2025
- *2024* Reviewer for CVPR 2024, ECCV 2024, ACM MM 2024, MIRU 2024
- *2022* IST-RA: A Doctoral Student Special Incentives Program provided by the University of Tokyo Graduate School of Information Science and Technology.
- *2020* Kaggle Global Wheat Detection Competition Silver Medal.
- *2020* MIRU Student Encouragement Award

</div>
