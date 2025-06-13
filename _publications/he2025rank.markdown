---
layout: publication
title: 'Rasa: Rank-sharing Low-rank Adaptation'
authors: Zhiwei He, Zhaopeng Tu, Xing Wang, Xingyu Chen, Zhijie Wang, Jiahao Xu, Tian Liang, Wenxiang Jiao, Zhuosheng Zhang, Rui Wang
conference: "Arxiv"
year: 2025
bibkey: he2025rank
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12576"}
  - {name: "Code", url: "https://github.com/zwhe99/RaSA"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Low-rank adaptation (LoRA) has been prominently employed for
parameter-efficient fine-tuning of large language models (LLMs). However, the
limited expressive capacity of LoRA, stemming from the low-rank constraint, has
been recognized as a bottleneck, particularly in rigorous tasks like code
generation and mathematical reasoning. To address this limitation, we introduce
Rank-Sharing Low-Rank Adaptation (RaSA), an innovative extension that enhances
the expressive capacity of LoRA by leveraging partial rank sharing across
layers. By forming a shared rank pool and applying layer-specific weighting,
RaSA effectively increases the number of ranks without augmenting parameter
overhead. Our theoretically grounded and empirically validated approach
demonstrates that RaSA not only maintains the core advantages of LoRA but also
significantly boosts performance in challenging code and math tasks. Code, data
and scripts are available at: https://github.com/zwhe99/RaSA.
