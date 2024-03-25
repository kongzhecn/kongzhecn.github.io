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



I am working towards a Ph.D. degree at Sun Yat-sen University, under the supervision of Prof.[Wenhan Luo](https://whluo.github.io/). 
Before, I received the M.E. degree from Shenzhen University, China, 2023 and under the supervision of Prof.[Feng Liu](https://scholar.google.com/citations?user=45uLWocAAAAJ) and Prof.[Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ).
I have published papers in journals, including TIFS, TNNLS. 
Previously, I interned at Tencent. My research interests include generative models and image/video synthesis.



# 🔥 News
- *2023.04*: &nbsp;🎉🎉 I join Sun Yat-sen University to pursue the Ph.D. degree under the supervision of Wenhan Luo!
- *2023.02*: &nbsp;🎉🎉 One paper is accepted by TNNLS!
- *2022.08*: &nbsp;🎉🎉 One paper is accepted by TIFS!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='https://github.com/kongzhecn/omg-project/blob/gh-pages/static/images/teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OMG: Occlusion-friendly Personalized Multi-concept Generation in Diffusion Models](https://arxiv.org/abs/2403.10983)

**Zhe Kong**, Yong Zhang, Tianyu Yang, Tao Wang, Kaihao Zhang, Bizhu Wu, Guanying Chen, Wei Liu, Wenhan Luo
-  In this work, we propose OMG, an occlusion-friendly personalized generation framework designed to seamlessly integrate multiple concepts within a single image. We propose a novel two-stage sampling solution. The first stage takes charge of layout generation and visual comprehension information collection for handling occlusions. The second one utilizes the acquired visual comprehension information and the designed noise blending to integrate multiple concepts while considering occlusions. We also observe that the initiation denoising timestep for noise blending is the key to identity preservation and layout. Moreover, our method can be combined with various single-concept models, such as LoRA and InstantID without additional tuning. Especially, LoRA models on Civitai.com can be exploited directly.
- [**[Page]**](https://kongzhecn.github.io/omg-project/) [**[Code]**](https://github.com/kongzhecn/dfdm) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS</div><img src='images/dfdm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taming Self-Supervised Learning for Presentation Attack Detection: De-Folding and De-Mixing](https://ieeexplore.ieee.org/abstract/document/10051654)

**Zhe Kong**, Wentian Zhang, Feng Liu, Wenhan Luo, Haozhe Liu, Linlin Shen, Raghavendra Ramachandra
- We proposed a self-supervised learning-based method, denoted as DF-DM. Specifically, DF-DM is based on a global-local view coupled with De-Folding and De-Mixing to derive the task-specific representation for PAD. During De-Folding, the proposed technique will learn region-specific features to represent samples in a local pattern by explicitly minimizing generative loss. While De-Mixing drives detectors to obtain the instance-specific features with global information for more comprehensive representation by minimizing interpolation-based consistency.
- [**Code**](https://github.com/kongzhecn/dfdm) 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS</div><img src='images/cfd-pad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Fingerprint Presentation Attack Detection by Channel-Wise Feature Denoising](https://ieeexplore.ieee.org/document/9851680)

Feng Liu, **Zhe Kong**, Haozhe Liu, Wentian Zhang, Linlin Shen

- This paper proposes a novel channel-wise feature denoising fingerprint PAD (CFD-PAD) method by handling the redundant noise information ignored in previous studies. The proposed method learns important features of fingerprint images by weighing the importance of each channel and identifying discriminative channels and “noise" channels. Then, the propagation of “noise" channels is suppressed in the feature map to reduce interference. Specifically, a PA-Adaptation loss is designed to constrain the feature distribution to make the feature distribution of live fingerprints more aggregate and that of spoof fingerprints more disperse.
- [**Code**](https://github.com/kongzhecn/cfd-pad) 
</div>
</div>

### Publication List
- [OMG: Occlusion-friendly Personalized Multi-concept Generation in Diffusion Models (2024)](https://arxiv.org/abs/2403.10983). **Zhe Kong**, Yong Zhang, Tianyu Yang, Tao Wang, Kaihao Zhang, Bizhu Wu, Guanying Chen, Wei Liu, Wenhan Luo, **Arxiv**
- Dual Teacher Knowledge Distillation with Domain Alignment for Face Anti-spoofing. (2024) **Zhe Kong**, Wentian Zhang, Tao Wang, Kaihao Zhang, Yuexiang Li, Xiaoying Tang, Wenhan Luo, **Arxiv**
- [Taming Self-Supervised Learning for Presentation Attack Detection: De-Folding and De-Mixing (2023)](https://ieeexplore.ieee.org/abstract/document/10051654) **Zhe Kong**, Wentian Zhang, Feng Liu, Wenhan Luo, Haozhe Liu, Linlin Shen, Raghavendra Ramachandra, **TNNLS**
- [Fingerprint Presentation Attack Detection by Channel-Wise Feature Denoising (2022)](https://ieeexplore.ieee.org/document/9851680) Feng Liu, **Zhe Kong**, Haozhe Liu, Wentian Zhang, Linlin Shen, **TIFS**

# 💻 Internships
- *2022.03 - 2022.11*, Tencent, China.

# 🎖 Honors and Awards
- 2023 Outstanding Graduate Award (Rate<5%)
- 2022 Excellent Academic Scholarship, First Class.
- 2021 Excellent Academic Scholarship, First Class.
- 2020 Freshman Scholarship, First Class.

<!--
# 📖 Educations
- *2023.09 - (now)*, Sun Yat-sen University. 
- *2020.09 - 2023.06*, Shenzhen University. 
- *2016.09 - 2020.06*, South China Agricultural University. 
-->

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->


<!--
# 💬 Professional Service

### Conference Reviewer 
- ACM MM: 2023
-->
