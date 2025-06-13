---
layout: publication
title: 'Recurrent Context Compression: Efficiently Expanding The Context Window Of LLM'
authors: Chensen Huang, Guibo Zhu, Xuepeng Wang, Yifei Luo, Guojing Ge, Haoran Chen, Dong Yi, Jinqiao Wang
conference: "Arxiv"
year: 2024
bibkey: huang2024recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06110"}
  - {name: "Code", url: "https://github.com/WUHU-G/RCC_Transformer"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code']
---
To extend the context length of Transformer-based large language models
(LLMs) and improve comprehension capabilities, we often face limitations due to
computational resources and bounded memory storage capacity. This work
introduces a method called Recurrent Context Compression (RCC), designed to
efficiently expand the context window length of LLMs within constrained storage
space. We also investigate the issue of poor model responses when both
instructions and context are compressed in downstream tasks, and propose an
instruction reconstruction method to mitigate this problem. We validated the
effectiveness of our approach on multiple tasks, achieving a compression rate
of up to 32x on text reconstruction tasks with a BLEU4 score close to 0.95, and
nearly 100% accuracy on a passkey retrieval task with a sequence length of 1M.
Finally, our method demonstrated competitive performance in long-text
question-answering tasks compared to non-compressed methods, while
significantly saving storage resources in long-text inference tasks. Our code,
models, and demo are available at https://github.com/WUHU-G/RCC_Transformer
