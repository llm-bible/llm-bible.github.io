---
layout: publication
title: 'I-code V2: An Autoregressive Generation Framework Over Vision, Language, And Speech Data'
authors: Ziyi Yang, Mahmoud Khademi, Yichong Xu, Reid Pryzant, Yuwei Fang, Chenguang Zhu, Dongdong Chen, Yao Qian, Mei Gao, Yi-ling Chen, Robert Gmyr, Naoyuki Kanda, Noel Codella, Bin Xiao, Yu Shi, Lu Yuan, Takuya Yoshioka, Michael Zeng, Xuedong Huang
conference: "Arxiv"
year: 2023
bibkey: yang2023i
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.12311'}
tags: ['RAG', 'Training Techniques', 'Tools', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
The convergence of text, visual, and audio data is a key step towards
human-like artificial intelligence, however the current Vision-Language-Speech
landscape is dominated by encoder-only models which lack generative abilities.
We propose closing this gap with i-Code V2, the first model capable of
generating natural language from any combination of Vision, Language, and
Speech data. i-Code V2 is an integrative system that leverages state-of-the-art
single-modality encoders, combining their outputs with a new modality-fusing
encoder in order to flexibly project combinations of modalities into a shared
representational space. Next, language tokens are generated from these
representations via an autoregressive decoder. The whole framework is
pretrained end-to-end on a large collection of dual- and single-modality
datasets using a novel text completion objective that can be generalized across
arbitrary combinations of modalities. i-Code V2 matches or outperforms
state-of-the-art single- and dual-modality baselines on 7 multimodal tasks,
demonstrating the power of generative multimodal pretraining across a diversity
of tasks and signals.
