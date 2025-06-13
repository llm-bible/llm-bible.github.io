---
layout: publication
title: 'ERPO: Advancing Safety Alignment Via Ex-ante Reasoning Preference Optimization'
authors: Kehua Feng, Keyan Ding, Jing Yu, Menghan Li, Yuhao Wang, Tong Xu, Xinda Wang, Qiang Zhang, Huajun Chen
conference: "Arxiv"
year: 2025
bibkey: feng2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02725"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Recent advancements in large language models (LLMs) have accelerated progress
toward artificial general intelligence, yet their potential to generate harmful
content poses critical safety challenges. Existing alignment methods often
struggle to cover diverse safety scenarios and remain vulnerable to adversarial
attacks. In this work, we propose Ex-Ante Reasoning Preference Optimization
(ERPO), a novel safety alignment framework that equips LLMs with explicit
preemptive reasoning through Chain-of-Thought and provides clear evidence for
safety judgments by embedding predefined safety rules. Specifically, our
approach consists of three stages: first, equipping the model with Ex-Ante
reasoning through supervised fine-tuning (SFT) using a constructed reasoning
module; second, enhancing safety, usefulness, and efficiency via Direct
Preference Optimization (DPO); and third, mitigating inference latency with a
length-controlled iterative preference optimization strategy. Experiments on
multiple open-source LLMs demonstrate that ERPO significantly enhances safety
performance while maintaining response efficiency.
