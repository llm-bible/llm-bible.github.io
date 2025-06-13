---
layout: publication
title: 'Mse-adapter: A Lightweight Plugin Endowing Llms With The Capability To Perform Multimodal Sentiment Analysis And Emotion Recognition'
authors: Yang Yang, Xunde Dong, Yupeng Qiang
conference: "Arxiv"
year: 2025
bibkey: yang2025mse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12478"}
tags: ['Multimodal Models', 'Training Techniques', 'Survey Paper', 'Tools']
---
Current Multimodal Sentiment Analysis (MSA) and Emotion Recognition in
Conversations (ERC) methods based on pre-trained language models exhibit two
primary limitations:
  1) Once trained for MSA and ERC tasks, these pre-trained language models lose
their original generalized capabilities. 2) They demand considerable
computational resources. As the size of pre-trained language models continues
to grow, training larger multimodal sentiment analysis models using previous
approaches could result in unnecessary computational cost. In response to this
challenge, we propose \textbf\{M\}ultimodal \textbf\{S\}entiment Analysis and
\textbf\{E\}motion Recognition \textbf\{Adapter\} (MSE-Adapter), a lightweight and
adaptable plugin. This plugin enables a large language model (LLM) to carry out
MSA or ERC tasks with minimal computational overhead (only introduces
approximately 2.6M to 2.8M trainable parameters upon the 6/7B models), while
preserving the intrinsic capabilities of the LLM. In the MSE-Adapter, the
Text-Guide-Mixer (TGM) module is introduced to establish explicit connections
between non-textual and textual modalities through the Hadamard product. This
allows non-textual modalities to better align with textual modalities at the
feature level, promoting the generation of higher-quality pseudo tokens.
Extensive experiments were conducted on four public English and Chinese
datasets using consumer-grade GPUs and open-source LLMs (Qwen-1.8B,
ChatGLM3-6B-base, and LLaMA2-7B) as the backbone. The results demonstrate the
effectiveness of the proposed plugin. The code will be released on GitHub after
a blind review.
