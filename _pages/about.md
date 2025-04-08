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

Hi, this is Qiqi! I'm currently a Doctor of Philosophy (PhD) candidate in Computer Science at the Shanghai Key Laboratory of Scalable Computing and Systems, Shanghai Jiao Tong University. I earned my Master of Engineering in Software Engineering from Shanghai Jiao Tong University between September 2020 and March 2023, advised by Prof. Jianguo Yao. Previously, I obtained my Bachelor of Engineering in Software Engineering from Nanjing University, graduating in 2020 after commencing my studies in 2016.

My research interests includes **System Optimization for Artificial Intelligence and High-Performance Computation (HPC)**. Notably, my work on uncovering the structured sparsity patterns within Large Language Models (LLMs) and accelerating Mixture-of-Experts (MoE) models through Sparse Tensor Cores has been accepted by EuroSys 2025. Additionally, I am currently engaged in researching methods to accelerate LLM Systems using emerging hardware technologies.

<!-- neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

- [*EuroSys'25*] Chenpeng Wu\*, **Qiqi Gu**\*, Heng Shi, Jianguo Yao, and Haibing Guan. Samoyeds: Accelerating MoE Models with Structured Sparsity Leveraging Sparse Tensor Cores, in Proceedings of the Twentieth European Conference on Computer Systems. 2025: 293-310.

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.04 - now*, Doctor of Philosophy (PhD), Computer Science, Shanghai Jiao Tong University.
- *2020.09 - 2023-03*, Master of Engineering, Software Engineering, Shanghai Jiao Tong University.
- *2016.09 - 2020.06*, Bachelor of Engineering, Software Engineering, Nanjing University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->