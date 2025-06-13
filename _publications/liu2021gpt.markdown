---
layout: publication
title: 'GPT Understands, Too'
authors: Xiao Liu, Yanan Zheng, Zhengxiao Du, Ming Ding, Yujie Qian, Zhilin Yang, Jie Tang
conference: "Arxiv"
year: 2021
bibkey: liu2021gpt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2103.10385'}
tags: ['Few-Shot', 'Training Techniques', 'Model Architecture', 'GPT', 'Prompting', 'Applications']
---
Prompting a pretrained language model with natural language patterns has been
proved effective for natural language understanding (NLU). However, our
preliminary study reveals that manual discrete prompts often lead to unstable
performance -- e.g., changing a single word in the prompt might result in
substantial performance drop. We propose a novel method P-Tuning that employs
trainable continuous prompt embeddings in concatenation with discrete prompts.
Empirically, P-Tuning not only stabilizes training by minimizing the gap
between various discrete prompts, but also improves performance by a sizeable
margin on a wide range of NLU tasks including LAMA and SuperGLUE. P-Tuning is
generally effective for both frozen and tuned language models, under both the
fully-supervised and few-shot settings.
