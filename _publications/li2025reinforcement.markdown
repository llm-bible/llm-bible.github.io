---
layout: publication
title: 'RIVAL: Reinforcement Learning With Iterative And Adversarial Optimization For Machine Translation'
authors: Tianjiao Li, Mengran Yu, Chenyu Shi, Yanjun Zhao, Xiaojing Liu, Qiang Zhang, Qi Zhang, Xuanjing Huang, Jiayin Wang
conference: "Arxiv"
year: 2025
bibkey: li2025reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05070"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Applications']
---
Large language models (LLMs) possess strong multilingual capabilities, and combining Reinforcement Learning from Human Feedback (RLHF) with translation tasks has shown great potential. However, we observe that this paradigm performs unexpectedly poorly when applied to colloquial subtitle translation tasks. In this work, we investigate this issue and find that the offline reward model (RM) gradually diverges from the online LLM due to distributional shift, ultimately leading to undesirable training outcomes. To address this, we propose RIVAL, an adversarial training framework that formulates the process as a min-max game between the RM and the LLM. RIVAL iteratively updates the both models, with the RM trained to distinguish strong from weak translations (qualitative preference reward), and the LLM trained to enhance its translation for closing this gap. To stabilize training and improve generalizability, we also incorporate quantitative preference reward (e.g., BLEU) into the RM, enabling reference-free quality modeling aligned with human evaluation. Through extensive experiments, we demonstrate that the proposed adversarial training framework significantly improves upon translation baselines.
