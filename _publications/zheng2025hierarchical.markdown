---
layout: publication
title: 'Hierarchical Masked Autoregressive Models With Low-resolution Token Pivots'
authors: Guangting Zheng, Yehao Li, Yingwei Pan, Jiajun Deng, Ting Yao, Yanyong Zhang, Tao Mei
conference: "Arxiv"
year: 2025
bibkey: zheng2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20288"}
  - {name: "Code", url: "https://github.com/HiDream-ai/himar"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Autoregressive models have emerged as a powerful generative paradigm for visual generation. The current de-facto standard of next token prediction commonly operates over a single-scale sequence of dense image tokens, and is incapable of utilizing global context especially for early tokens prediction. In this paper, we introduce a new autoregressive design to model a hierarchy from a few low-resolution image tokens to the typical dense image tokens, and delve into a thorough hierarchical dependency across multi-scale image tokens. Technically, we present a Hierarchical Masked Autoregressive models (Hi-MAR) that pivot on low-resolution image tokens to trigger hierarchical autoregressive modeling in a multi-phase manner. Hi-MAR learns to predict a few image tokens in low resolution, functioning as intermediary pivots to reflect global structure, in the first phase. Such pivots act as the additional guidance to strengthen the next autoregressive modeling phase by shaping global structural awareness of typical dense image tokens. A new Diffusion Transformer head is further devised to amplify the global context among all tokens for mask token prediction. Extensive evaluations on both class-conditional and text-to-image generation tasks demonstrate that Hi-MAR outperforms typical AR baselines, while requiring fewer computational costs. Code is available at https://github.com/HiDream-ai/himar.
