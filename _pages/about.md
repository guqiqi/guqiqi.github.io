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

Hi, this is Qiqi! I'm a PhD student in Computer Science at the Shanghai Key Laboratory of Scalable Computing and Systems, Shanghai Jiao Tong University. I received my Master of Engineering in Software Engineering from Shanghai Jiao Tong University in 2023, advised by Prof. Jianguo Yao, and my Bachelor of Engineering in Software Engineering from Nanjing University in 2020.

My research focuses on **System Optimization for Artificial Intelligence and High-Performance Computing (HPC)**, with an emphasis on hardware-aware algorithms and GPU kernel optimization. I explore how computational structure, sparsity, and modern GPU architectures can be exploited together to accelerate workloads ranging from large language models (LLMs) to scientific computing.

<!-- neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.04 - now*, Doctor of Philosophy (PhD), Computer Science, Shanghai Jiao Tong University.
- *2020.09 - 2023-03*, Master of Engineering, Software Engineering, Shanghai Jiao Tong University.
- *2016.09 - 2020.06*, Bachelor of Engineering, Software Engineering, Nanjing University.

# 📝 Publications 

- [*SC'26*] **Qiqi Gu**\*, Chenpeng Wu\*, Heng Shi, Jianguo Yao, and Haibing Guan. Do We Need Tensor Cores for Stencil Computations?, in Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis. 2026. **Best Student Paper Nominee.** [\[Code\]](https://github.com/KevinWu2017/HORSE)
- [*SC'26*] Heng Shi, **Qiqi Gu**, Chenpeng Wu, Xiaofeng Guan, Sijie Wu, Enming Fan, Guoqing Bao, and Jianguo Yao. Pushing the Limits of Structured Sparse GEMM on Hopper GPUs via Analytical Modeling, in Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis. 2026.
- [ATC'26] Chenpeng Wu\*, **Qiqi Gu**\*, Heng Shi, Jianguo Yao, and Haibing Guan. SptcAttn: Accelerating Long-Context Attention with Diagonal Stripes using Sparse Tensor Core, in Proceedings of The 2026 ACM SIGOPS Annual Technical Conference. 2026.
- [ATC'26] Heng Shi, Xiaofeng Guan, Sijie Wu, Enming Fan, Chenpeng Wu, **Qiqi Gu**, Jiahang Xie, Guoqing Bao, and Jianguo Yao. A Novel AI-Native GPU Kernel Programming Language for Autonomous Kernel Tuning, in Proceedings of The 2026 ACM SIGOPS Annual Technical Conference. 2026.
- [*PPoPP'26*] **Qiqi Gu**\*, Chenpeng Wu\*, Heng Shi, and Jianguo Yao. SPIDER: Unleashing Sparse Tensor Cores for Stencil Computation via Strided Swapping, in Proceedings of the 31st ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming. 2026. [\[Code\]](https://github.com/KevinWu2017/SPIDER) [\[Paper\]](https://doi.org/10.1145/3774934.3786414)
- [*EuroSys'25*] Chenpeng Wu\*, **Qiqi Gu**\*, Heng Shi, Jianguo Yao, and Haibing Guan. Samoyeds: Accelerating MoE Models with Structured Sparsity Leveraging Sparse Tensor Cores, in Proceedings of the Twentieth European Conference on Computer Systems. 2025: 293-310. [\[Code\]](https://github.com/guqiqi/Samoyeds) [\[Paper\]](https://doi.org/10.1145/3689031.3717455)

# 📜 Patents

- [CN121525859B] 姚建国，袁航宇，吴晨鹏，**顾琦琪**。混合专家模型的异构推理加速方法及系统。
- [CN119808860B] 姚建国，吴晨鹏，**顾琦琪**，石恒，张亚林。混合专家模型的优化方法、装置、设备、介质及程序。
- [CN119808861B] 姚建国，吴晨鹏，**顾琦琪**，石恒，张亚林。混合专家模型的存储优化方法、装置、设备、介质及产品。
- [CN119830976B] 姚建国，吴晨鹏，**顾琦琪**，石恒，张亚林。混合专家模型的算子优化方法、装置、设备、介质及程序。
- [CN119806639B] 姚建国，吴晨鹏，**顾琦琪**，石恒，张亚林。双稀疏矩阵的乘法加速方法、装置、设备、介质及产品。
- [CN116126806B] 姚建国，**顾琦琪**，管海兵。基于 NVM 混合内存的可扩展文件系统、方法、介质及设备。
- [CN114138423B] 高毅，姚建国，余学俊，**顾琦琪**。基于国产 GPU 显卡的虚拟化构建系统及方法。

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2026.06 - 2026.09*, NVIDIA, [TensorRT LLM](https://github.com/NVIDIA/TensorRT-LLM) Developer.
