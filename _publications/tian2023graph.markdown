---
layout: publication
title: Graph Neural Prompting With Large Language Models
authors: Tian Yijun, Song Huan, Wang Zichen, Wang Haozhu, Hu Ziqing, Wang Fang, Chawla Nitesh V., Xu Panpan
conference: "Arxiv"
year: 2023
bibkey: tian2023graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15427"}
  - {name: "Code", url: "https://github.com/meettyj/GNP"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have shown remarkable generalization capability with exceptional performance in various language modeling tasks. However they still exhibit inherent limitations in precisely capturing and returning grounded knowledge. While existing work has explored utilizing knowledge graphs (KGs) to enhance language modeling via joint training and customized model architectures applying this to LLMs is problematic owing to their large number of parameters and high computational cost. Therefore how to enhance pre45;trained LLMs using grounded knowledge e.g. retrieval45;augmented generation remains an open question. In this work we propose Graph Neural Prompting (GNP) a novel plug45;and45;play method to assist pre45;trained LLMs in learning beneficial knowledge from KGs. GNP encompasses various designs including a standard graph neural network encoder a cross45;modality pooling module a domain projector and a self45;supervised link prediction objective. Extensive experiments on multiple datasets demonstrate the superiority of GNP on both commonsense and biomedical reasoning tasks across different LLM sizes and settings. Code is available at https://github.com/meettyj/GNP.
