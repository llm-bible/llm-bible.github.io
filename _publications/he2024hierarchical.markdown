---
layout: publication
title: 'HMT: Hierarchical Memory Transformer For Efficient Long Context Language Processing'
authors: Zifan He, Yingqi Cao, Zongyue Qin, Neha Prakriya, Yizhou Sun, Jason Cong
conference: "Arxiv"
year: 2024
bibkey: he2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06067"}
  - {name: "Code", url: "https://github.com/OswaldHe/HMT-pytorch"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
Transformer-based large language models (LLM) have been widely used in
language processing applications. However, due to the memory constraints of the
devices, most of them restrict the context window. Even though recurrent models
in previous works can memorize past tokens to enable unlimited context and
maintain effectiveness, they have ``flat'' memory architectures. Such
architectures have limitations in selecting and filtering information. Since
humans are good at learning and self-adjustment, we believe that imitating
brain memory hierarchy is beneficial for model memorization. Thus, we propose
the Hierarchical Memory Transformer (HMT), a novel framework that facilitates a
model's long-context processing ability by imitating human memorization
behavior. Leveraging memory-augmented segment-level recurrence, we organize the
memory hierarchy by preserving tokens from early input segments, passing memory
embeddings along the sequence, and recalling relevant information from history.
Evaluating general language modeling, question-answering tasks, and the
summarization task, we show that HMT consistently improves the long-context
processing ability of existing models. Furthermore, HMT achieves a comparable
or superior generation quality to long-context LLMs with \\(2 \sim 57\times\\)
fewer parameters and \\(2.5 \sim 116\times\\) less inference memory, significantly
outperforming previous memory-augmented models. Code on Github:
https://github.com/OswaldHe/HMT-pytorch.
