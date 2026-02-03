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

I am currently a MPhil student at HKUST(GZ) under the mentorship of Prof. [Xuming Hu](https://xuminghu.github.io/). I'm also collaborating with Prof. [Mingxun Zhou](https://wuwuz.github.io/) at HKUST on AI governance. Before that I received my B.S. degree in Data Science at Tongji University, where I had the privilege of being advised by Prof. [Zhihua Wei](https://see.tongji.edu.cn/info/1379/10345.htm). I am honored to have collaborated with distinguished researchers such as [Yibo Yan](https://stupidbuluchacha.github.io/), [Kaichen Huang](https://www.lamda.nju.edu.cn/huangkc/) and [Na Min An](https://namin-an.github.io/).  
My research interests lie at the intersection of multimodal and trustworthy AI, with an additional focus on generative models, semantic watermarking, and interpretability. Beyond my research, I am also deeply passionate about mathematics, programming, and data visualization. 


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper submitted to ICML'26.
- *2026.01*: &nbsp;🎉🎉 One paper accepted by ICLR'26!
- *2025.09*: &nbsp;🎉🎉 Code of [PMark](https://github.com/PMark-repo/PMark) released.
- *2025.09*: &nbsp;🎉🎉 One paper submitted to ICLR'26.
- *2025.06*: &nbsp;🎉🎉 Code of [MMUnlearner](https://github.com/Z1zs/MMUnlearner) released.
- *2025.05*: &nbsp;🎉🎉 Two paper accepted by ACL'25 Findings, one paper accepted by ACL'25 (Industry) Oral!
- *2025.02*: &nbsp;🎉🎉 One paper submitted to ACL'25.
- *2024.09*: &nbsp;🎉🎉 Code of [MMNeuron](https://github.com/Z1zs/MMNeuron) released.
- *2024.09*: &nbsp;🎉🎉 One paper accepted by EMNLP'24!
- *2024.06*: &nbsp;🎉🎉 One paper submitted to EMNLP'24.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/causalembed.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CausalEmbed: Auto-Regressive Multi-Vector Generation in Latent Space for Visual Document Embedding](https://arxiv.org/abs/2601.21262)

**Jiahao Huo**, Yu Huang, Yibo Yan, Ye Pan, Yi Cao, Mingdong Ou, Philip S. Yu, Xuming Hu

[**Project**](https://github.com/Z1zs/Causal-Embed) <strong><span class='show_paper_citations' data=''></span></strong>
- Auto-regressive embedding generation for multi-vector visual document retrieval.
- 30-155x reduction in token count and test-time sclaing for retrieval performance. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/pmark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PMark: Towards Robust and Distortion-free Semantic-level Watermarking with Channel Constraints](https://arxiv.org/abs/2509.21057v1)

**Jiahao Huo**, Shuliang Liu, Bin Wang, Junyan Zhang, Yibo Yan, Aiwei Liu, Xuming Hu, Mingxun Zhou

[**Project**](https://github.com/PMark-repo/PMark) <strong><span class='show_paper_citations' data=''></span></strong>
- Novel and unified theoretical framework on semantic-level watermarking.
- Distortion-free and robust semantic-level watermarking for LLMs.  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL'25 Findings</div><img src='images/mmunlearner.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://arxiv.org/abs/2502.11051)

**<u>Jiahao Huo</u>**, <u>Yibo Yan</u>, Xu Zheng, Yuanhuiyi Lyu, Xin Zou, Zhihua Wei, Xuming Hu

[**Project**](https://github.com/Z1zs/MMUnlearner) <strong><span class='show_paper_citations' data='SJQZDGUAAAAJ:zYLM7Y9cAGgC'></span></strong>
- Reformulate the task of multimodal MU in the era of MLLMs.  
- Aims to erase only the visual patterns associated with a given entity while preserving the corresponding textual knowledge encoded within the original parameters of the language model backbone.  
- Develop a novel geometry-constrained gradient ascent method MMUnlearner.  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL'25 (Industry) Oral</div><img src='images/math_agent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MathAgent: Leveraging a Mixture-of-Math-Agent Framework for Real-World Multimodal Mathematical Error Detection](https://arxiv.org/abs/2503.18132)

Yibo Yan, Shen Wang, **Jiahao Huo**, Philip S. Yu, Xuming Hu, Qingsong Wenpng

[**Project**](https://arxiv.org/abs/2503.18132) <strong><span class='show_paper_citations' data='SJQZDGUAAAAJ:d1gkVwhDpl0C'></span></strong>
- Decomposes error detection into three phases
- Each phase handled by a specialized agent: an image-text consistency validator, a visual semantic interpreter, and an integrative error analyzer.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP'24 main</div><img src='images/mmneuron.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMNeuron: Discovering Neuron-Level Domain-Specific Interpretation in Multimodal Large Language Model](https://arxiv.org/abs/2406.11193)

**Jiahao Huo**, Yibo Yan, Boren Hu, Yutao Yue, Xuming Hu

[**Project**](https://github.com/Z1zs/MMNeuron) <strong><span class='show_paper_citations' data='SJQZDGUAAAAJ:u5HHmVD_uO8C'></span></strong>
- Investigating the distribution of domain-specific neurons and the mechanism of how MLLMs process features from diverse domains.
</div>
</div>


# 📖 Educations
- *2021.09 - 2025.07*, Undergraduate Student, Tongji University.
- *2024.10 - 2025.03*, Exchange Student, Technical University of Munich.
- *2025.10 - present*, MPhil Student, HKUST(GZ).

# 💻 Internships
- *2025.06 - 2025.09*, Intern, Alibaba Group
- *2025.05 - 2025.07*, Visiting Student, Institute for Advanced Algorithms Research (IRRA), Shanghai
- *2024.02 - 2024.10*, Intern, HKUST(GZ).

# 📝 Services
- Conferences: ACL(2025 SRW, 2026), ICLR(LLM Reason and Plan Workshop)
