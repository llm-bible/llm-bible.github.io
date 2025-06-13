---
layout: publication
title: 'Zebra: Extending Context Window With Layerwise Grouped Local-global Attention'
authors: Kaiqiang Song, Xiaoyang Wang, Sangwoo Cho, Xiaoman Pan, Dong Yu
conference: "Arxiv"
year: 2023
bibkey: song2023extending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08618"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
This paper introduces a novel approach to enhance the capabilities of Large
Language Models (LLMs) in processing and understanding extensive text
sequences, a critical aspect in applications requiring deep comprehension and
synthesis of large volumes of information. Recognizing the inherent challenges
in extending the context window for LLMs, primarily built on Transformer
architecture, we propose a new model architecture, referred to as Zebra. This
architecture efficiently manages the quadratic time and memory complexity
issues associated with full attention in the Transformer by employing grouped
local-global attention layers. Our model, akin to a zebra's alternating
stripes, balances local and global attention layers, significantly reducing
computational requirements and memory consumption. Comprehensive experiments,
including pretraining from scratch, continuation of long context adaptation
training, and long instruction tuning, are conducted to evaluate the Zebra's
performance. The results show that Zebra achieves comparable or superior
performance on both short and long sequence benchmarks, while also enhancing
training and inference efficiency.
