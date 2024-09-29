---
layout: publication
title: 'DELIA: Diversity-enhanced Learning For Instruction Adaptation In Large Language Models'
authors: Zeng Yuanhao, Ren Fei, Zhou Xinpeng, Wang Yihang, Shao Yingxia
conference: "Arxiv"
year: 2024
bibkey: zeng2024diversity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10841"}
tags: ['Applications', 'Ethics And Bias', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Although instruction tuning is widely used to adjust behavior in Large Language Models (LLMs) extensive empirical evidence and research indicates that it is primarily a process where the model fits to specific task formats rather than acquiring new knowledge or capabilities. We propose that this limitation stems from biased features learned during instruction tuning which differ from ideal task-specfic features leading to learn less underlying semantics in downstream tasks. However ideal features are unknown and incalculable constraining past work to rely on prior knowledge to assist reasoning or training which limits LLMs capabilities to the developers abilities rather than data-driven scalable learning. In our paper through our novel data synthesis method DELIA (Diversity-Enhanced Learning for Instruction Adaptation) we leverage the buffering effect of extensive diverse data in LLMs training to transform biased features in instruction tuning into approximations of ideal features without explicit prior ideal features. Experiments show DELIAs better performance compared to common instruction tuning and other baselines. It outperforms common instruction tuning by 17.0737;-33.4137; on Icelandic-English translation bleurt score (WMT-21 dataset gemma-7b-it) and improves accuracy by 36.137; on formatted text generation (Llama2-7b-chat). Notably among knowledge injection methods weve known DELIA uniquely align the internal representations of new special tokens with their prior semantics.
