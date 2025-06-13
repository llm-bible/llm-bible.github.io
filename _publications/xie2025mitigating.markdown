---
layout: publication
title: 'TARAC: Mitigating Hallucination In Lvlms Via Temporal Attention Real-time Accumulative Connection'
authors: Chunzhao Xie, Tongxuan Liu, Lei Jiang, Yuting Zeng, Jinrong Guo, Yunheng Shen, Weizhe Huang, Jing Li, Xiaohua Xu
conference: "Arxiv"
year: 2025
bibkey: xie2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04099"}
tags: ['Ethics and Bias', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Large Vision-Language Models have demonstrated remarkable performance across
various tasks; however, the challenge of hallucinations constrains their
practical applications. The hallucination problem arises from multiple factors,
including the inherent hallucinations in language models, the limitations of
visual encoders in perception, and biases introduced by multimodal data.
Extensive research has explored ways to mitigate hallucinations. For instance,
OPERA prevents the model from overly focusing on "anchor tokens", thereby
reducing hallucinations, whereas VCD mitigates hallucinations by employing a
contrastive decoding approach. In this paper, we investigate the correlation
between the decay of attention to image tokens and the occurrence of
hallucinations. Based on this finding, we propose Temporal Attention Real-time
Accumulative Connection (TARAC), a novel training-free method that dynamically
accumulates and updates LVLMs' attention on image tokens during generation. By
enhancing the model's attention to image tokens, TARAC mitigates hallucinations
caused by the decay of attention on image tokens. We validate the effectiveness
of TARAC across multiple models and datasets, demonstrating that our approach
substantially mitigates hallucinations. In particular, TARAC reduces \\(C_S\\) by
25.2 and \\(C_I\\) by 8.7 compared to VCD on the CHAIR benchmark.
