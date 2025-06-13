---
layout: publication
title: 'Towards Infinite-long Prefix In Transformer'
authors: Yingyu Liang, Zhenmei Shi, Zhao Song, Chiwun Yang
conference: "Arxiv"
year: 2024
bibkey: liang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14036"}
  - {name: "Code", url: "https://github.com/ChristianYang37/chiwun/tree/main/src/NTK-Attention"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Prompting and context-based fine-tuning methods, which we call Prefix
Learning, have been proposed to enhance the performance of language models on
various downstream tasks. They are empirically efficient and effective,
matching the performance of full parameter fine-tuning, but the theoretical
understandings are limited. In this paper, we aim to address this limitation by
studying their ability from the perspective of prefix length. In particular, we
provide a convergence guarantee for training an ultra-long prefix in a stylized
setting using the Neural Tangent Kernel (NTK) framework. Based on this strong
theoretical guarantee, we design and implement an algorithm that only needs to
introduce and fine-tune a few extra trainable parameters instead of an
infinite-long prefix in each layer of a transformer, and can approximate the
prefix attention to a guaranteed polynomial-small error. Preliminary
experimental results on vision, natural language, and math data show that our
method achieves superior or competitive performance compared to existing
methods like full parameters fine-tuning, P-Tuning V2, and LoRA. This
demonstrates our method is promising for parameter-efficient fine-tuning. Our
code can be found at
\url\{https://github.com/ChristianYang37/chiwun/tree/main/src/NTK-Attention\}.
