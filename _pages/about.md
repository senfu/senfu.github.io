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

My research interest lies in multimodal foundation model and embodied AI.

# 🔥 News


- *2024.08* [FlexAttention](https://arxiv.org/abs/2407.20228) is accepted by **ECCV2024**. Check our [Project Page](https://vis-www.cs.umass.edu/flexattention/) and also [GitHub![img](https://img.shields.io/github/stars/UMass-Foundation-Model/FlexAttention?style=social)](https://github.com/UMass-Foundation-Model/FlexAttention)
- *2024.01* [CoVLM](https://arxiv.org/abs/2311.03354) is accepted by **ICLR2024**. Check our [Project Page](https://vis-www.cs.umass.edu/CoVLM/) and also [GitHub![img](https://img.shields.io/github/stars/UMass-Foundation-Model/CoVLM?style=social)](https://github.com/UMass-Foundation-Model/CoVLM).
- *2023.07* [EfficientViT](https://arxiv.org/abs/2205.14756) is accepted by **ICCV2023**. Check it on [GitHub![img](https://img.shields.io/github/stars/mit-han-lab/efficientvit?style=social)](https://github.com/mit-han-lab/efficientvit).
- *2023.06* [ToP](https://dl.acm.org/doi/abs/10.1145/3580305.3599284) is accepted by **KDD2023**. Check it on [GitHub![img](https://img.shields.io/github/stars/microsoft/Moonlit?style=social)](https://github.com/microsoft/Moonlit/tree/main/ToP).
- *2023.03* [ProxylessGaze](https://github.com/mit-han-lab/proxylessnas/tree/master/proxyless_gaze) is publicly available as an application of [ProxylessNAS![img](https://img.shields.io/github/stars/mit-han-lab/proxylessnas?style=social)](https://github.com/mit-han-lab/proxylessnas). It is an open-source gaze estimation pipeline including face detection, facial landmark detection and gaze estimation, running in real time on Raspberry Pi 4, Qualcomm GPU and Intel CPU.

# 📝 Publications



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV2024</div><img src='images/flexattention/intro.jpg' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlexAttention for Efficient High-Resolution Vision-Language Models](https://arxiv.org/pdf/2407.20228)

**Junyan Li**, Delin Chen, Tianle Cai, Peihao Chen, Yining Hong, Zhenfang Chen, Yikang Shen, Chuang Gan

[**GitHub** ![](https://img.shields.io/github/stars/UMass-Foundation-Model/FlexAttention?style=social)](https://github.com/UMass-Foundation-Model/FlexAttention) | [**Project Page**](https://vis-www.cs.umass.edu/flexattention/)

- FlexAttention is a plug-and-play attention module that can enhance VLMs' ability to perceive details in high resolution image in an efficient way.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2024</div><img src='images/covlm/intro.png' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding
](https://arxiv.org/pdf/2311.03354.pdf)

**Junyan Li**, Delin Chen, Yining Hong, Zhenfang Chen, Peihao Chen, Yikang Shen, Chuang Gan

[**GitHub** ![](https://img.shields.io/github/stars/UMass-Foundation-Model/CoVLM?style=social)](https://github.com/UMass-Foundation-Model/CoVLM) | [**Project Page**](https://vis-www.cs.umass.edu/CoVLM/)

- CoVLM is specifically designed to guide the VLM to explicitly compose visual entities and relationships among the text and dynamically communicate with the vision encoder and detection network to achieve vision-language communicative decoding. It boosts the compositional reasoning ability of VLMs and achieve SoTA performance on various tasks involving compositional analysis.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2023</div><img src='images/efficientvit/intro.png' alt="efficientvit_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EfficientViT: Lightweight Multi-Scale Attention for On-Device Semantic Segmentation](https://arxiv.org/pdf/2205.14756.pdf)

Han Cai, **Junyan Li**, Muyan Hu, Chuang Gan, Song Han

[**GitHub** ![](https://img.shields.io/github/stars/mit-han-lab/efficientvit?style=social)](https://github.com/mit-han-lab/efficientvit) | [**Poster**](images/efficientvit/poster.png)

- EfficientViT is a new family of vision models for efficient high-resolution vision, especially segmentation. The core building block of EfficientViT is a new lightweight multi-scale attention module that achieves global receptive field and multi-scale learning with only hardware-efficient operations.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD2023</div><img src='images/top/intro.png' alt="top_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Constraint-aware and Ranking-distilled Token Pruning for Efficient Transformer Inference](https://dl.acm.org/doi/abs/10.1145/3580305.3599284)

**Junyan Li**, Li Lyna Zhang, Jiahang Xu, Yujing Wang, Shaoguang Yan, Yunqing Xia, Yuqing Yang, Ting Cao, Hao Sun, Weiwei Deng, Qi Zhang, Mao Yang

[**GitHub**![](https://img.shields.io/github/stars/microsoft/Moonlit?style=social)](https://github.com/microsoft/Moonlit/tree/main/ToP) | [**Poster**](images/top/poster.png)

- ToP is a deployment friendly token pruning solution for Transformers.

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

- *2024.06 - 2024.08*,  [Toyota Research Institute](https://www.tri.global/), Los Altos, USA
- *2023.05 - 2023.08*, [NVIDIA](https://www.nvidia.com/en-us/), Shanghai, China.
- *2022.08 - 2023.02*, [Microsoft Research Lab - Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), Beijing, China.
- *2021.06 - 2021.08*, [Momenta](https://www.momenta.cn/), Beijing, China.
