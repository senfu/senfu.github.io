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

I am currently a first-year PhD student in computer science at the University of Massachusetts Amherst, advised by Prof. Chuang Gan. Previously, I was an undergraduate at Zhejiang University and the University of Illinois Urbana-Champaign.

My research interest lies in efficient machine learning, foundation models and multimodal reasoning.


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2023.03* [ProxylessGaze](https://github.com/mit-han-lab/proxylessnas/tree/master/proxyless_gaze) is publicly available as an application of [ProxylessNAS ![](https://img.shields.io/github/stars/mit-han-lab/proxylessnas?style=social)](https://github.com/mit-han-lab/proxylessnas). It is an open-source gaze estimation pipeline including face detection, facial landmark detection and gaze estimation, running in real time on Raspberry Pi 4, Qualcomm GPU and Intel CPU.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/efficientvit/intro.png' alt="efficientvit_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EfficientViT: Lightweight Multi-Scale Attention for On-Device Semantic Segmentation](https://arxiv.org/pdf/2205.14756.pdf)

Han Cai, **Junyan Li**, Muyan Hu, Chuang Gan, Song Han

[**GitHub** ![](https://img.shields.io/github/stars/mit-han-lab/efficientvit?style=social)](https://github.com/mit-han-lab/efficientvit) | [**Poster**](images/efficientvit/poster.png) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- EfficientViT is a new family of vision models for efficient high-resolution vision, especially segmentation. The core building block of EfficientViT is a new lightweight multi-scale attention module that achieves global receptive field and multi-scale learning with only hardware-efficient operations.
</div>
</div>


# 🎖 Honors and Awards
- *2022.11* Zhejiang Provincial Scholarship
- *2022.11* Zhejiang University Second Scholarship
- *2020.11* Zhejiang University Second Scholarship

# 📖 Educations
- *2023.09 - (now)*, PhD, computer science, University of Massachusetts Amherst. 
- *2019.09 - 2023.06*, Undergraduate, computer engineering, University of Illinois Urbana-Champaign.
- *2019.09 - 2023.06*, Undergraduate, computer engineering, Zhejiang University.

# 💻 Internships
- *2023.05 - 2023.08*, [NVIDIA](https://www.nvidia.com/en-us/), Shanghai, China.
- *2022.08 - 2023.02*, [Microsoft Research Lab - Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China.
- *2021.06 - 2021.08*, [Momenta](https://www.momenta.cn/), Beijing, China.
