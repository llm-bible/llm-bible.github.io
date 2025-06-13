---
layout: publication
title: 'Mastering Text, Code And Math Simultaneously Via Fusing Highly Specialized Language Models'
authors: Ning Ding, Yulin Chen, Ganqu Cui, Xingtai Lv, Weilin Zhao, Ruobing Xie, Bowen Zhou, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: ding2024mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08281"}
tags: ['Tools', 'Training Techniques', 'Reinforcement Learning']
---
Underlying data distributions of natural language, programming code, and
mathematical symbols vary vastly, presenting a complex challenge for large
language models (LLMs) that strive to achieve high performance across all three
domains simultaneously. Achieving a very high level of proficiency for an LLM
within a specific domain often requires extensive training with relevant
corpora, which is typically accompanied by a sacrifice in performance in other
domains. In this paper, we propose to fuse models that are already
highly-specialized directly. The proposed fusing framework, UltraFuser,
consists of three distinct specialists that are already sufficiently trained on
language, coding, and mathematics. A token-level gating mechanism is introduced
to blend the specialists' outputs. A two-stage training strategy accompanied by
balanced sampling is designed to ensure stability. To effectively train the
fused model, we further construct a high-quality supervised instruction tuning
dataset, UltraChat 2, which includes text, code, and mathematical content. This
dataset comprises approximately 300,000 instructions and covers a wide range of
topics in each domain. Experiments show that our model could simultaneously
achieve mastery of the three crucial domains.
