---
layout: publication
title: 'Scaling Laws With Vocabulary: Larger Models Deserve Larger Vocabularies'
authors: Chaofan Tao, Qian Liu, Longxu Dou, Niklas Muennighoff, Zhongwei Wan, Ping Luo, Min Lin, Ngai Wong
conference: "Arxiv"
year: 2024
bibkey: tao2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13623"}
  - {name: "Code", url: "https://github.com/sail-sg/scaling-with-vocab"}
  - {name: "Code", url: "https://hf.co/spaces/sail/scaling-with-vocab-demo"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Tokenization', 'Has Code', 'Scaling Laws']
---
Research on scaling large language models (LLMs) has primarily focused on
model parameters and training data size, overlooking the role of vocabulary
size. We investigate how vocabulary size impacts LLM scaling laws by training
models ranging from 33M to 3B parameters on up to 500B characters with various
vocabulary configurations. We propose three complementary approaches for
predicting the compute-optimal vocabulary size: IsoFLOPs analysis, derivative
estimation, and parametric fit of the loss function. Our approaches converge on
the conclusion that the optimal vocabulary size depends on the compute budget,
with larger models requiring larger vocabularies. Most LLMs, however, use
insufficient vocabulary sizes. For example, we predict that the optimal
vocabulary size of Llama2-70B should have been at least 216K, 7 times larger
than its vocabulary of 32K. We validate our predictions empirically by training
models with 3B parameters across different FLOPs budgets. Adopting our
predicted optimal vocabulary size consistently improves downstream performance
over commonly used vocabulary sizes. By increasing the vocabulary size from the
conventional 32K to 43K, we improve performance on ARC-Challenge from 29.1 to
32.0 with the same 2.3e21 FLOPs. Our work highlights the importance of jointly
considering tokenization and model scaling for efficient pre-training. The code
and demo are available at https://github.com/sail-sg/scaling-with-vocab and
https://hf.co/spaces/sail/scaling-with-vocab-demo.
