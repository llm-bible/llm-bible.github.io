---
layout: publication
title: 'Breaking The Stage Barrier: A Novel Single-stage Approach To Long Context Extension For Large Language Models'
authors: Haoran Lian, Junmin Chen, Wei Huang, Yizhe Xiong, Wenping Hu, Guiguang Ding, Hui Chen, Jianwei Niu, Zijia Lin, Fuzheng Zhang, Di Zhang
conference: "Arxiv"
year: 2024
bibkey: lian2024breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07171"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Attention Mechanism']
---
Recently, Large language models (LLMs) have revolutionized Natural Language
Processing (NLP). Pretrained LLMs, due to limited training context size,
struggle with handling long token sequences, limiting their performance on
various downstream tasks. Current solutions toward long context modeling often
employ multi-stage continual pertaining, which progressively increases the
effective context length through several continual pretraining stages. However,
those approaches require extensive manual tuning and human expertise. In this
paper, we introduce a novel single-stage continual pretraining method,
Head-Adaptive Rotary Position Encoding (HARPE), to equip LLMs with long context
modeling capabilities while simplifying the training process. Our HARPE
leverages different Rotary Position Encoding (RoPE) base frequency values
across different attention heads and directly trains LLMs on the target context
length. Extensive experiments on 4 language modeling benchmarks, including the
latest RULER benchmark, demonstrate that HARPE excels in understanding and
integrating long-context tasks with single-stage training, matching and even
outperforming existing multi-stage methods. Our results highlight that HARPE
successfully breaks the stage barrier for training LLMs with long context
modeling capabilities.
