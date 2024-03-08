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



I am working towards a Ph.D. degree in Sun Yat-sen University, under the supervision of Prof.[Wenhan Luo](https://whluo.github.io/). 
Before, I received the M.E. degree from Shenzhen University, China, 2023 and under the supervision of Prof.[Feng Liu](https://scholar.google.com/citations?user=45uLWocAAAAJ) and Prof.[Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ).
I have published several papers in journals, including TIFS, TNNLS. 
Previously, I interned at Tencent. My research interests include face anti-spoofing, self-supervised learning and multimodal.



# 🔥 News
- *2023.04*: &nbsp;🎉🎉 I join Sun Yat-sen University to pursue the Ph.D. degree under the supervision of Wenhan Luo!
- *2023.02*: &nbsp;🎉🎉 One paper is accepted by TNNLS!
- *2022.08*: &nbsp;🎉🎉 One paper is accepted by TIFS!

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taming Self-Supervised Learning for Presentation Attack Detection: De-Folding and De-Mixing](https://ieeexplore.ieee.org/abstract/document/10051654)

**Zhe Kong**, Wentian Zhang, Feng Liu, Wenhan Luo, Haozhe Liu, Linlin Shen, Raghavendra Ramachandra
- Biometric systems are vulnerable to Presentation Attacks (PA) performed using various Presentation Attack Instruments (PAIs). Even though there are numerous Presentation Attack Detection (PAD) techniques based on both deep learning and hand-crafted features, the generalization of PAD for unknown PAI is still a challenging problem. In this work, we empirically prove that the initialization of the PAD model is a crucial factor for the generalization, which is rarely discussed in the community. Based on such observation, we proposed a self-supervised learning-based method, denoted as DF-DM. Specifically, DF-DM is based on a global-local view coupled with De-Folding and De-Mixing to derive the task-specific representation for PAD. During De-Folding, the proposed technique will learn region-specific features to represent samples in a local pattern by explicitly minimizing generative loss. While De-Mixing drives detectors to obtain the instance-specific features with global information for more comprehensive representation by minimizing interpolation-based consistency. Extensive experimental results show that the proposed method can achieve significant improvements in terms of both face and fingerprint PAD in more complicated and hybrid datasets when compared with state-of-the-art methods. When training in CASIA-FASD and Idiap Replay-Attack, the proposed method can achieve an 18.60\% Equal Error Rate (EER) in  OULU-NPU and MSU-MFSD, exceeding baseline performance by 9.54\%.
- [**Code**](https://github.com/kongzhecn/dfdm) 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Fingerprint Presentation Attack Detection by Channel-Wise Feature Denoising](https://ieeexplore.ieee.org/document/9851680)

Feng Liu, **Zhe Kong**, Haozhe Liu, Wentian Zhang, Linlin Shen

[**Code**]([https://github.com/kongzhecn/cfd-pad](https://github.com/kongzhecn/cfd-pad)) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>



- [Taming Self-Supervised Learning for Presentation Attack Detection: De-Folding and De-Mixing](https://ieeexplore.ieee.org/abstract/document/10051654) **Zhe Kong**, Wentian Zhang, Feng Liu, Wenhan Luo, Haozhe Liu, Linlin Shen, Raghavendra Ramachandra, **TNNLS**
- [Fingerprint Presentation Attack Detection by Channel-Wise Feature Denoising](https://ieeexplore.ieee.org/document/9851680) Feng Liu, **Zhe Kong**, Haozhe Liu, Wentian Zhang, Linlin Shen, **TIFS**


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

# 💻 Internships
- *2022.03 - 2022.11*, Tencent, China.

# 💬 Professional Service

### Conference Reviewer 
- ACM MM: 2023
