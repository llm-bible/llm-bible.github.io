---
layout: publication
title: 'Latency Adjustable Transformer Encoder For Language Understanding'
authors: Sajjad Kachuee, Mohammad Sharifkhani
conference: "Arxiv"
year: 2022
bibkey: kachuee2022latency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.03327"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Adjusting the latency, power, and accuracy of natural language understanding
models is a desirable objective of an efficient architecture. This paper
proposes an efficient Transformer architecture that adjusts the inference
computational cost adaptively with a desired inference latency speedup. In
fine-tuning phase, the proposed method detects less important hidden sequence
elements (word-vectors) and eliminates them in each encoder layer using a
proposed Attention Context Contribution (ACC) metric. After the fine-tuning
phase, with the novel offline-tuning property, the inference latency of the
model can be adjusted in a wide range of inference speedup selections without
any further training. Extensive experiments reveal that most word-vectors in
higher Transformer layers contribute less to subsequent layers, allowing their
removal to improve inference latency. Experimental results on various language
understanding, text generation, and instruction tuning tasks and benchmarks
demonstrate the approach's effectiveness across diverse datasets, with minimal
impact on the input's global context. The technique improves
Time-to-First-Token (TTFT) of Llama3 by up to 2.9x, with minor performance
drop. The suggested approach posits that in Large Language Models (LLMs),
although the complete network is necessary for training, it can be truncated
during the fine-tuning phase.
