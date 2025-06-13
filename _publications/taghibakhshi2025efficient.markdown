---
layout: publication
title: 'Efficient Hybrid Language Model Compression Through Group-aware SSM Pruning'
authors: Ali Taghibakhshi, Sharath Turuvekere Sreenivas, Saurav Muralidharan, Marcin Chochowski, Yashaswi Karnati, Raviraj Joshi, Ameya Sunil Mahabaleshwarkar, Zijia Chen, Yoshi Suhara, Oluwatobi Olabiyi, Daniel Korzekwa, Mostofa Patwary, Mohammad Shoeybi, Jan Kautz, Bryan Catanzaro, Ashwath Aithal, Nima Tajbakhsh, Pavlo Molchanov
conference: "Arxiv"
year: 2025
bibkey: taghibakhshi2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11409"}
tags: ['Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Quantization', 'Distillation']
---
Hybrid LLM architectures that combine Attention and State Space Models (SSMs)
achieve state-of-the-art accuracy and runtime performance. Recent work has
demonstrated that applying compression and distillation to Attention-only
models yields smaller, more accurate models at a fraction of the training cost.
In this work, we explore the effectiveness of compressing Hybrid architectures.
We introduce a novel group-aware pruning strategy that preserves the structural
integrity of SSM blocks and their sequence modeling capabilities. Furthermore,
we demonstrate the necessity of such SSM pruning to achieve improved accuracy
and inference speed compared to traditional approaches. Our compression recipe
combines SSM, FFN, embedding dimension, and layer pruning, followed by
knowledge distillation-based retraining, similar to the MINITRON technique.
Using this approach, we compress the Nemotron-H 8B Hybrid model down to 4B
parameters with up to 40x fewer training tokens. The resulting model surpasses
the accuracy of similarly-sized models while achieving 2x faster inference,
significantly advancing the Pareto frontier.
