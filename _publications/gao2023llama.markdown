---
layout: publication
title: 'Llama-adapter V2: Parameter-efficient Visual Instruction Model'
authors: Peng Gao, Jiaming Han, Renrui Zhang, Ziyi Lin, Shijie Geng, Aojun Zhou, Wei Zhang, Pan Lu, Conghui He, Xiangyu Yue, Hongsheng Li, Yu Qiao
conference: "Arxiv"
year: 2023
bibkey: gao2023llama
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2304.15010'}
  - {name: "Code", url: 'https://github.com/ZrrSkywalker/LLaMA-Adapter'}
tags: ['Has Code', 'GPT', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
How to efficiently transform large language models (LLMs) into instruction
followers is recently a popular research direction, while training LLM for
multi-modal reasoning remains less explored. Although the recent LLaMA-Adapter
demonstrates the potential to handle visual inputs with LLMs, it still cannot
generalize well to open-ended visual instructions and lags behind GPT-4. In
this paper, we present LLaMA-Adapter V2, a parameter-efficient visual
instruction model. Specifically, we first augment LLaMA-Adapter by unlocking
more learnable parameters (e.g., norm, bias and scale), which distribute the
instruction-following ability across the entire LLaMA model besides adapters.
Secondly, we propose an early fusion strategy to feed visual tokens only into
the early LLM layers, contributing to better visual knowledge incorporation.
Thirdly, a joint training paradigm of image-text pairs and
instruction-following data is introduced by optimizing disjoint groups of
learnable parameters. This strategy effectively alleviates the interference
between the two tasks of image-text alignment and instruction following and
achieves strong multi-modal reasoning with only a small-scale image-text and
instruction dataset. During inference, we incorporate additional expert models
(e.g. captioning/OCR systems) into LLaMA-Adapter to further enhance its image
understanding capability without incurring training costs. Compared to the
original LLaMA-Adapter, our LLaMA-Adapter V2 can perform open-ended multi-modal
instructions by merely introducing 14M parameters over LLaMA. The newly
designed framework also exhibits stronger language-only instruction-following
capabilities and even excels in chat interactions. Our code and models are
available at https://github.com/ZrrSkywalker/LLaMA-Adapter.
