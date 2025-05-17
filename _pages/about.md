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

I am a senior undergraduate student in Data Science at Tongji University, where I have the privilege of being advised by Prof. [Zhihua Wei](https://see.tongji.edu.cn/info/1379/10345.htm). Since February 2024, I have been an intern at HKUST (Guangzhou) under the mentorship of Dr. [Xuming Hu](https://xuminghu.github.io/). I am honored to have collaborated with distinguished researchers such as [Weize Liu](https://aclanthology.org/people/w/weize-liu/), [Yibo Yan](https://stupidbuluchacha.github.io/) and [Kaichen Huang](https://www.lamda.nju.edu.cn/huangkc/).  
My research interests lie at the intersection of multimodal and explainable AI, with an additional focus on generative models, machine unlearning, and differential privacy. Beyond my research, I am also deeply passionate about mathematics, programming, and data visualization.


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 Two paper accepted by ACL'25 Findings, one paper accepted by ACL'25 (Industry) Oral!
- *2025.02*: &nbsp;🎉🎉 One paper submitted to ACL'25.
- *2024.09*: &nbsp;🎉🎉 Code of [MMNeuron](https://github.com/Z1zs/MMNeuron) released.
- *2024.09*: &nbsp;🎉🎉 One paper accepted by EMNLP'24!
- *2024.06*: &nbsp;🎉🎉 One paper submitted to EMNLP'24.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL'25 Findings</div><img src='images/mmunlearner.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://arxiv.org/abs/2502.11051)

**<u>Jiahao Huo</u>**, <u>Yibo Yan</u>, Xu Zheng, Yuanhuiyi Lyu, Xin Zou, Zhihua Wei, Xuming Hu

[**Project**](https://arxiv.org/abs/2502.11051) <strong><span class='show_paper_citations' data='SJQZDGUAAAAJ:zYLM7Y9cAGgC'></span></strong>
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
- *2021.09 - present*, Undergraduate Student, Tongji University. 

# 💻 Internships
- *2025.05 - present*, Visiting Student, Institute for Advanced Algorithms Research (IRRA), Shanghai
- *2024.10 - 2025.03*, Visiting Student, Technical University of Munich.
- *2024.02 - 2024.10*, Intern, HKUST(GZ).
