---
layout: publication
title: 'Graph Neural Prompting With Large Language Models'
authors: Yijun Tian, Huan Song, Zichen Wang, Haozhu Wang, Ziqing Hu, Fang Wang, Nitesh V. Chawla, Panpan Xu
conference: "Arxiv"
year: 2023
bibkey: tian2023graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15427"}
  - {name: "Code", url: "https://github.com/meettyj/GNP"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
Large language models (LLMs) have shown remarkable generalization capability
with exceptional performance in various language modeling tasks. However, they
still exhibit inherent limitations in precisely capturing and returning
grounded knowledge. While existing work has explored utilizing knowledge graphs
(KGs) to enhance language modeling via joint training and customized model
architectures, applying this to LLMs is problematic owing to their large number
of parameters and high computational cost. Therefore, how to enhance
pre-trained LLMs using grounded knowledge, e.g., retrieval-augmented
generation, remains an open question. In this work, we propose Graph Neural
Prompting (GNP), a novel plug-and-play method to assist pre-trained LLMs in
learning beneficial knowledge from KGs. GNP encompasses various designs,
including a standard graph neural network encoder, a cross-modality pooling
module, a domain projector, and a self-supervised link prediction objective.
Extensive experiments on multiple datasets demonstrate the superiority of GNP
on both commonsense and biomedical reasoning tasks across different LLM sizes
and settings. Code is available at https://github.com/meettyj/GNP.
