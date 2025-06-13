---
layout: publication
title: 'Sequence-level Large Language Model Training With Contrastive Preference Optimization'
authors: Zhili Feng, Dhananjay Ram, Cole Hawkins, Aditya Rawal, Jinman Zhao, Sheng Zha
conference: "Arxiv"
year: 2025
bibkey: feng2025sequence
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16433'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Applications', 'Training Techniques']
---
The next token prediction loss is the dominant self-supervised training
objective for large language models and has achieved promising results in a
variety of downstream tasks. However, upon closer investigation of this
objective, we find that it lacks an understanding of sequence-level signals,
leading to a mismatch between training and inference processes. To bridge this
gap, we introduce a contrastive preference optimization (CPO) procedure that
can inject sequence-level information into the language model at any training
stage without expensive human labeled data. Our experiments show that the
proposed objective surpasses the next token prediction in terms of win rate in
the instruction-following and text generation tasks.
