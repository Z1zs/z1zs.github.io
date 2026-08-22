---
permalink: /
title: "Jiahao Huo"
excerpt: "MPhil in Artificial Intelligence"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an MPhil student in Artificial Intelligence at the Hong Kong University of Science and Technology (Guangzhou), where I am supervised by [Prof. Xuming Hu](https://xuminghu.github.io/). I have also had the opportunity to work with [Prof. Mingxun Zhou](https://wuwuz.github.io/) at HKUST and [Prof. Philip S. Yu](https://cs.uic.edu/profiles/philip-yu/) at the University of Illinois Chicago. Previously, I earned my B.S. in Data Science from Tongji University.

My research focuses on **LLM post-training**, **multimodal learning**, **agent memory**, and **trustworthy AI**. I am particularly interested in understanding why learning methods work and translating those insights into reliable, practical systems. I am grateful to have collaborated with [Weize Liu](https://attention-is-all-i-need.github.io/), [Yibo Yan](https://stupidbuluchacha.github.io/), [Kaichen Huang](https://www.lamda.nju.edu.cn/huangkc/), [Na Min An](https://namin-an.github.io/), [Wenjie Qu](https://quwenjie.github.io/), [Kening Zheng](https://init-neok.github.io/), and [Weiwei Sun](https://sunnweiwei.github.io/). I also sincerely appreciate the guidance and support I have received from all my mentors and collaborators.

You can find my work on [Google Scholar](https://scholar.google.com/citations?user=SJQZDGUAAAAJ), [GitHub](https://github.com/Z1zs), and [OpenReview](https://openreview.net/profile?id=%7EJiahao_Huo2).


# 🔥 News
- *2026 02*: Released **CausalEmbed**, an autoregressive multi-vector approach to visual document embedding.
- *2026.01*: **PMark** was accepted by ICLR 2026 through a direct submission.
- *2025.09*: One paper submited to ICLR 2026.
- *2025 04*: Joined [MemoryOS](https://github.com/MemTensor/MemOS) as a core developer.
- *2025.05*: **MMUnlearner** was accepted by ACL 2025 Findings. 
- *2025.05*: **MathAgent** was selected as an ACL 2025 Industry Track oral paper.
- *2025.02*: Two paper submited to ACL 2025.
- *2024.09*: **MMNeuron** was accepted by EMNLP 2024 Main.
- *2024.06*: One paper submited to EMNLP 2024.

# 🔬 Research Interests
- **Post-training and distillation:** on-policy distillation, reasoning models, and efficient adaptation.
- **Multimodal representation learning:** compact visual-document representations and generative embeddings.
- **Agent memory:** persistent, retrievable, and multimodal memory for AI agents.
- **Trustworthy AI:** text watermarking, machine unlearning, and model interpretability.

# 📝 Selected Publications

Selected publications are listed below; see [Google Scholar](https://scholar.google.com/citations?user=SJQZDGUAAAAJ) for the full list.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review · 2026</div><img src='projects/SAMark/assets/overview.png' alt="SAMark overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAMark: A Self-Anchored Text Watermarking with Paragraph-Level Paraphrase Robustness](/SAMark/)

**Jiahao Huo**, Wenjie Qu, Yibo Yan, Kening Zheng, Jiaheng Zhang, Xuming Hu, Philip S. Yu, Mingxun Zhou

- A self-anchored semantic watermarking framework designed to remain detectable under paragraph-level paraphrase attacks while preserving generation quality.

[arXiv](https://arxiv.org/abs/2605.25796) · [Code](https://github.com/Z1zs/SAMark) · [Project](/SAMark/)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='projects/PMark/assets/framework.jpg' alt="PMark framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PMark: Towards Robust and Distortion-Free Semantic-Level Watermarking with Channel Constraints](/PMark/)

**Jiahao Huo**, Shuliang Liu, Bin Wang, Junyan Zhang, Yibo Yan, Aiwei Liu, Xuming Hu, Mingxun Zhou

- A semantic watermarking method that encodes detectable structure through jointly constrained channels while preserving the language model's sampling distribution.

[arXiv](https://arxiv.org/abs/2509.21057) · [Code](https://github.com/PMark-repo/PMark) · [Project](/PMark/)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review · 2026</div><img src='projects/CausalEmbed/assets/framework.jpg' alt="CausalEmbed framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CausalEmbed: Auto-Regressive Multi-Vector Generation in Latent Space for Visual Document Embedding](/CausalEmbed/)

**Jiahao Huo**, Yu Huang, Yibo Yan, Ye Pan, Yi Cao, Mingdong Ou, Philip S. Yu, Xuming Hu

- An autoregressive latent-space embedding model that represents visual documents with compact multi-vector sequences and supports controllable late-interaction retrieval.

[arXiv](https://arxiv.org/abs/2601.21262) · [Code](https://github.com/Z1zs/Causal-Embed) · [Project](/CausalEmbed/)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Findings</div><img src='projects/MMUnlearner/assets/framework.jpg' alt="MMUnlearner framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](/MMUnlearner/)

**Jiahao Huo**, Yibo Yan, Xu Zheng, Yuanhuiyi Lyu, Xin Zou, Zhihua Wei, Xuming Hu

- A modality-aware unlearning framework that suppresses target visual concepts through saliency-guided, geometry-constrained updates while retaining textual knowledge and general visual capabilities.

[arXiv](https://arxiv.org/abs/2502.11051) · [Code](https://github.com/Z1zs/MMUnlearner) · [Project](/MMUnlearner/)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Industry Track · Oral</div><img src='images/mathagent_acl25.png' alt="MathAgent paper overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MathAgent: Leveraging a Mixture-of-Math-Agent Framework for Real-World Multimodal Mathematical Error Detection](https://arxiv.org/abs/2503.18132)

Yibo Yan, Shen Wang, **Jiahao Huo**, Philip S. Yu, Xuming Hu, Qingsong Wen

- A mixture-of-agents framework for multimodal mathematical error detection, combining image–text consistency validation, visual semantic interpretation, and integrative error analysis.

[arXiv](https://arxiv.org/abs/2503.18132)

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024 Main</div><img src='projects/MMNeuron/assets/framework.jpg' alt="MMNeuron framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMNeuron: Discovering Neuron-Level Domain-Specific Interpretation in Multimodal Large Language Models](/MMNeuron/)

**Jiahao Huo**, Yibo Yan, Boren Hu, Yutao Yue, Xuming Hu

- An interpretability framework that identifies domain-specific neurons, traces their contribution to multimodal predictions, and validates their causal effect through controlled intervention.

[arXiv](https://arxiv.org/abs/2406.11193) · [Code](https://github.com/Z1zs/MMNeuron) · [Project](/MMNeuron/)

</div></div>

Additional publications:
- Unveiling Language Routing Isolation in Multilingual MoE Models for Interpretable Subnetwork Adaptation - Kening Zheng, Wei-Chieh Huang, **Jiahao Huo**, Zhonghao Li, Henry Peng Zou, Yibo Yan, Xin Zou, Jungang Li, Junzhuo Li, Hanrong Zhang, Xuming Hu, Philip S. Yu. *EMNLP 2026 Findings.* [Paper](https://arxiv.org/abs/2604.03592)
- **ErrorRadar:** Benchmarking Complex Mathematical Reasoning of Multimodal Large Language Models via Error Detection — Yibo Yan, Shen Wang, **Jiahao Huo**, Hang Li, Boyan Li, Jiamin Su, Xiong Gao, Yi-Fan Zhang, Tianlong Xu, Zhendong Chu, Aoxiao Zhong, Kun Wang, Hui Xiong, Philip S. Yu, Xuming Hu, Qingsong Wen. *ACL 2026 Findings.* [Paper](https://arxiv.org/abs/2410.04509)
- **Pierce the Mists, Greet the Sky:** Decipher Knowledge Overshadowing via Knowledge Circuit Analysis — Haoming Huang, Yibo Yan, **Jiahao Huo**, Xin Zou, Xinfeng Li, Kun Wang, Xuming Hu. *EMNLP 2025.* [Paper](https://arxiv.org/abs/2505.14406) · [Code](https://github.com/halfmorepiece/PhantomCircuit)
- **EssayJudge:** A Multi-Granular Benchmark for Assessing Automated Essay Scoring Capabilities of MLLMs — Jiamin Su, Yibo Yan, Fangteng Fu, Han Zhang, Jingheng Ye, Xiang Liu, **Jiahao Huo**, Huiyu Zhou, Xuming Hu. *ACL 2025 Findings.* [Paper](https://arxiv.org/abs/2502.11916)
- **MemOS:** A Memory OS for AI System — Zhiyu Li, Shichao Song, Chenyang Xi, Hanyu Wang, Chen Tang, Simin Niu, Ding Chen, Jiawei Yang, Chunyu Li, Qingchen Yu, Jihao Zhao, Yezhaohui Wang, Peng Liu, Zehao Lin, Pengyuan Wang, **Jiahao Huo**, Tianyi Chen, Kai Chen, Kehang Li, Zhen Tao, Huayi Lai, Hao Wu, Bo Tang, Zhenren Wang, Zhaoxin Fan, Ningyu Zhang, Linfeng Zhang, Junchi Yan, Mingchuan Yang, Tong Xu, Wei Xu, Huajun Chen, Haofen Wang, Hongkang Yang, Wentao Zhang, Zhi-Qin John Xu, Siheng Chen, Feiyu Xiong. *Technical report.* [Paper](https://arxiv.org/abs/2507.03724) · [Code](https://github.com/MemTensor/MemOS)
- **Explainable and Interpretable Multimodal Large Language Models:** A Comprehensive Survey — Yunkai Dang, Kaichen Huang, **Jiahao Huo**, Yibo Yan, Sirui Huang, Dongrui Liu, Mengxi Gao, Jie Zhang, Chen Qian, Kun Wang, Yong Liu, Jing Shao, Hui Xiong, Xuming Hu. *Preprint.* [Paper](https://arxiv.org/abs/2412.02104)
- **Memory in the Age of AI Agents** — Yuyang Hu, Shichun Liu, Yanwei Yue, Guibin Zhang, Boyang Liu, Fangyi Zhu, Jiahang Lin, Honglin Guo, Shihan Dou, Zhiheng Xi, Senjie Jin, Jiejun Tan, Yanbin Yin, Jiongnan Liu, Zeyu Zhang, Zhongxiang Sun, Yutao Zhu, Hao Sun, Boci Peng, Zhenrong Cheng, Xuanbo Fan, Jiaxin Guo, Xinlei Yu, Zhenhong Zhou, Zewen Hu, **Jiahao Huo**, Junhao Wang, Yuwei Niu, Yu Wang, Zhenfei Yin, Xiaobin Hu, Yue Liao, Qiankun Li, Kun Wang, Wangchunshu Zhou, Yixin Liu, Dawei Cheng, Qi Zhang, Tao Gui, Shirui Pan, Yan Zhang, Philip Torr, Zhicheng Dou, Ji-Rong Wen, Xuanjing Huang, Yu-Gang Jiang, Shuicheng Yan. *Preprint.* [Paper](https://arxiv.org/abs/2512.13564)

# 📖 Educations
- *2025 – 2026*, **Hong Kong University of Science and Technology (Guangzhou)** — MPhil in Artificial Intelligence.
- *2024 – 2025*, **Technical University of Munich** — Exchange student, School of Computation, Information and Technology.
- *2021 – 2025*, **Tongji University** — B.S. in Data Science, GPA 91.65/100.

# 💼 Experience
- *Feb 2026 – Jun 2026*, **University of Illinois Chicago** — Visiting Student with Philip S. Yu; autoregressive multimodal embeddings, representation learning, and on-policy (self-)distillation.
- *Feb 2026 – Jun 2026*, **Alibaba Cloud Computing** — Research Intern with Mingdong Ou; compact visual-document representations and generative multimodal systems.
- *Jun 2025 – Sep 2025*, **Alibaba Group · Pixel Lab** — Machine Learning Engineer Intern with Chengfei Lyu; repository-scale code understanding, continued pre-training, and model merging.
- *Apr 2025 – Jun 2025*, **Institute for Advanced Algorithms Research & MemTensor** — Core Developer for [MemoryOS](https://github.com/MemTensor/MemOS); open-source memory infrastructure for AI agents and framework compatibility.
- *Feb 2024 – July 2024*, **Squirrel AI Learning** — Research Intern; semantic watermarking, multimodal unlearning and interpretation, and educational agents.

# 🧑‍⚖️ Academic Service
- **Conference reviewer:** ARR (2025, 2026), ACL 2026, EMNLP 2026, SIGIR 2026, and NeurIPS 2026.
- **Journal reviewer:** IEEE *Transactions on Neural Networks and Learning Systems* (TNNLS).
