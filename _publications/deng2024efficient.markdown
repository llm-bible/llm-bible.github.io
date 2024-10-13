---
layout: publication
title: 'ELASTIC: Efficient Linear Attention For Sequential Interest Compression'
authors: Deng Jiaxin, Wang Shiyao, Lu Song, Li Yinfeng, Luo Xinchen, Liu Yuanjun, Xu Peixing, Zhou Guorui
conference: "Arxiv"
year: 2024
bibkey: deng2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09380"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
State-of-the-art sequential recommendation models heavily rely on
transformer's attention mechanism. However, the quadratic computational and
memory complexities of self attention have limited its scalability for modeling
users' long range behaviour sequences. To address this problem, we propose
ELASTIC, an Efficient Linear Attention for SequenTial Interest Compression,
requiring only linear time complexity and decoupling model capacity from
computational cost. Specifically, ELASTIC introduces a fixed length interest
experts with linear dispatcher attention mechanism which compresses the
long-term behaviour sequences to a significantly more compact representation
which reduces up to 90% GPU memory usage with x2.7 inference speed up. The
proposed linear dispatcher attention mechanism significantly reduces the
quadratic complexity and makes the model feasible for adequately modeling
extremely long sequences. Moreover, in order to retain the capacity for
modeling various user interests, ELASTIC initializes a vast learnable interest
memory bank and sparsely retrieves compressed user's interests from the memory
with a negligible computational overhead. The proposed interest memory
retrieval technique significantly expands the cardinality of available interest
space while keeping the same computational cost, thereby striking a trade-off
between recommendation accuracy and efficiency. To validate the effectiveness
of our proposed ELASTIC, we conduct extensive experiments on various public
datasets and compare it with several strong sequential recommenders.
Experimental results demonstrate that ELASTIC consistently outperforms
baselines by a significant margin and also highlight the computational
efficiency of ELASTIC when modeling long sequences. We will make our
implementation code publicly available.
