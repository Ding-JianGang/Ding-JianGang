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

# Welcome!

I am a Ph.D. candidate at Chang'an University, conducting research on situational awareness in nearshore environments. My supervisor is Professor [**Li Wei**](https://js.chd.edu.cn/sjkxyrgzn/lw103/list.htm). My work focuses on multimodal fusion, multi-object tracking, and vision-language large models. Currently, I am deeply involved in AI Agent projects for specific scenarios as part of my doctoral research. In addition, I have conducted research on traditional computer vision (CV), edge computing, and C++ front-end development (QT) and have independently developed a complete set of front-end and back-end algorithms for industrial production (Digital Radiography imaging), which generated millions in value. If you're interested in my work, feel free to email me.


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 New Journal Paper on **LG-Diff: Learning to Follow Local Class-Regional Guidance for Nearshore Image Cross-modality High-Quality Translation** Accepted by **Information Fusion** (中科院一区, Top, IF=18.6, 第一作者).
- *2024.10*: &nbsp;🎉🎉 New Journal Paper on **SeaTrack: Rethinking Observation-Centric SORT for Robust Nearshore Multiple Object Tracking** Accepted by **Pattern Recognition** (中科院一区, Top, IF=8.0, 第一作者).
- *2024.10*: &nbsp;🎉🎉 New Conference Paper on **Learning to Follow Frequency View Guidance for Dental CT Images Deblurring** Accepted by **IEEE International Conference on Bioinformatics and Biomedicine 2024** (CCF-B, EI, 第一作者).
- *2024.10*: &nbsp;🎉🎉 New Journal Paper on **Crack instance segmentation using splittable transformer and position coordinates** Accepted by **Automation in Construction** (中科院一区, Top, IF=10.3, 通讯作者).
- *2024.09*: &nbsp;🎉🎉 New Journal Paper on **Nearshore optical video object detector based on temporal branch and spatial feature enhancement** Accepted by **Engineering Applications of Artificial Intelligence** (中科院二区, IF=8.0, 通讯作者).
- *2024.03*: &nbsp;🎉🎉 New Journal Paper on **Novel Pipeline Integrating Cross-Modality and Motion Model for Nearshore Multi-Object Tracking in Optical Video Surveillance** Accepted by **IEEE Transactions on Intelligent Transportation Systems** (中科院一区, Top, IF=8.5, 第一作者).
- *2023.03*: &nbsp;🎉🎉 New Journal Paper on **A coarse aggregate gradation detection method based on 3D point cloud** Accepted by **Construction and Building Materials** (中科院一区, Top, IF=7.6, 通讯作者).
- *2023.02*: &nbsp;🎉🎉 New Journal Paper on **Foreign Bodies Detector Based on DETR for High-Resolution X-Ray Images of Textiles** Accepted by **IEEE Transactions on Instrumentation and Measurement** (中科院一区, Top, IF=5.6, 第一作者).
- *2023.01*: &nbsp;🎉🎉 New Journal Paper on **Sw-YoloX: An anchor-free detector based transformer for sea surface object detection** Accepted by **Expert Systems With Applications** (中科院一区, Top, IF=8.6, 第一作者).

# 📝 Publications 
🎓 *Low-level tasks*
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFFUS 2024</div><img src='images/LG-Diff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LG-Diff: Learning to Follow Local Class-Regional Guidance for Nearshore Image Cross-modality High-Quality Translation](https://doi.org/10.1016/j.inffus.2024.102870) <br> **Jiangang Ding**, Yiquan Du, Wei Li, Lili Pei, Ningning Cui <br> [**Project**](https://github.com/Ding-JianGang/LG-Diff) <strong> | SCI Journal Paper</strong>
- Nearshore cross-modal translation is formulated as a denoising diffusion process.
- We develop a two-stage pipeline guided by local class-regional information.
- Decoupling high- and low-frequency information in the feature extraction.
- A cross-modal benchmark for nearshore image translation task is proposed.
</div>
</div>

🎓 *High-level tasks*
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR 2024</div><img src='images/SeaTrack.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SeaTrack: Rethinking Observation-Centric SORT for Robust Nearshore Multiple Object Tracking](https://doi.org/10.1016/j.patcog.2024.111091) <br> **Jiangang Ding**, Wei Li, Ming Yang, Yuanlin Zhao, Lili Pei, Aojia Tian <br> <strong> SCI Journal Paper</strong>
- We implemented a fully motion information-based pipeline for the NMOT challenge.
- Solve long-term occlusion problems through guiding modulation between objects.
- Confidence, height and corner information are used to reconstruct the tracker.
- Reduce tracking errors through long and short-term tracklets fusion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2024</div><img src='images/CrossModalityDetect.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Novel Pipeline Integrating Cross-Modality and Motion Model for Nearshore Multi-Object Tracking in Optical Video Surveillance](https://doi: 10.1109/TITS.2024.3373370) <br> **Jiangang Ding**, Wei Li, Lili Pei, Ming Yang, Aojia Tian, Bo Yuan <br> [**Project**](https://github.com/Ding-JianGang/Cross-Modality-MOT-in-Nearshore-Environments) <strong> | SCI Journal Paper</strong>
- We propose a holistic cross-modality NMOT pipeline based on optical video surveillance and demonstrate its state-of-the-art performance in multiple benchmark evaluations.
- We developed a simple yet effective CBT to decouple and guide the fusion of the RGB and thermal infrared video streams. Additionally, we introduce a Temporal Context Transformer to mitigate the various complex degradations caused by video signals by integrating feature information from the current and historical frames.
- We heuristically model the motion interrelationships of objects to compensate for the Kalman Filter prior estimates, synchronously combining low-confidence modeling and MCM to assist with association and tracklet correction.
</div>
</div>

# 🎖 Honors and Awards
- *2024.10*: First-Class Scholarship for Ph.D. Students (Top 10%)
- *2024.10*: National Scholarship for Ph.D. Students (**Top 1%**)
- *2023.10*: Excellent Ph.D. Student (Top 10%)
- *2022.10*: First-Class Scholarship for Master's Students (Top 10%)
- *2021.10*: Excellent Master's Student (Top 10%)
- *2021.10*: First-Class Scholarship for Master's Students (Top 10%)
- *2021.05*: First Prize in the Provincial "Challenge Cup" Competition (Ranked 2nd)

# 💻 Projects
- *2024.01 - 2026.01*, Fundamental Research Funds for the Central Universities (中央高校优博专项), **主持**
- *2023.12 - 2023.12*, Scientific Innovation Practice Project of Postgraduates of Chang'an University, **主持**
- *2020.09 - 2023.12*, National Natural Science Foundation, 参与, 核心人员
- *2023.06 - 2024.12*, National Key R&D Program, 参与, 核心人员

# 💬 Part-time Academic Job
Member of the China Society of Image and Graphics, Member of the Chinese Association for Artificial Intelligence, IEEE Student Member, [CSDN Blog Expert ](https://blog.csdn.net/qq_42308217?type=blog) (1 million views, **30,000** followers). Long-term reviewer for top journals and conferences in the field of Computer Science.

# 📖 Educations
- *September 2016 - June 2020*: Bachelor's in Measurement and Control Technology and Instruments, Chang'an University, Xi'an, China
- *September 2020 - June 2022*: Master's in Information and Communication Engineering, Chang'an University, Xi'an, China, Supervised by Professor Wei Li
- *September 2022 - June 2026* (now): Ph.D. in Traffic Information and Engineering, Chang'an University, Xi'an, China, Supervised by Professor Wei Li
