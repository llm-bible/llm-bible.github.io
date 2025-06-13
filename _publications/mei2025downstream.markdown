---
layout: publication
title: 'Veattack: Downstream-agnostic Vision Encoder Attack Against Large Vision Language Models'
authors: Hefei Mei, Zirui Wang, Shen You, Minjing Dong, Chang Xu
conference: "Arxiv"
year: 2025
bibkey: mei2025downstream
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17440"}
  - {name: "Code", url: "https://github.com/hfmei/VEAttack-LVLM"}
tags: ['Applications', 'Model Architecture', 'Security', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities in multimodal understanding and generation, yet their vulnerability to adversarial attacks raises significant robustness concerns. While existing effective attacks always focus on task-specific white-box settings, these approaches are limited in the context of LVLMs, which are designed for diverse downstream tasks and require expensive full-model gradient computations. Motivated by the pivotal role and wide adoption of the vision encoder in LVLMs, we propose a simple yet effective Vision Encoder Attack (VEAttack), which targets the vision encoder of LVLMs only. Specifically, we propose to generate adversarial examples by minimizing the cosine similarity between the clean and perturbed visual features, without accessing the following large language models, task information, and labels. It significantly reduces the computational overhead while eliminating the task and label dependence of traditional white-box attacks in LVLMs. To make this simple attack effective, we propose to perturb images by optimizing image tokens instead of the classification token. We provide both empirical and theoretical evidence that VEAttack can easily generalize to various tasks. VEAttack has achieved a performance degradation of 94.5% on image caption task and 75.7% on visual question answering task. We also reveal some key observations to provide insights into LVLM attack/defense: 1) hidden layer variations of LLM, 2) token attention differential, 3) M\"obius band in transfer attack, 4) low sensitivity to attack steps. The code is available at https://github.com/hfmei/VEAttack-LVLM
