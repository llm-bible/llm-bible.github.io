---
layout: publication
title: 'IAA: Inner-adaptor Architecture Empowers Frozen Large Language Model With Multimodal Capabilities'
authors: Wang Bin, Xie Chunyu, Leng Dawei, Yin Yuhui
conference: "Arxiv"
year: 2024
bibkey: wang2024inner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12902"}
  - {name: "Code", url: "https://github.com/360CVGroup/Inner-Adaptor-Architecture"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
'In the field of multimodal large language models (MLLMs), common methods typically involve unfreezing the language model during training to foster profound visual understanding. However, the fine-tuning of such models with vision-language data often leads to a diminution of their natural language processing (NLP) capabilities. To avoid this performance degradation, a straightforward solution is to freeze the language model while developing multimodal competencies. Unfortunately, previous works have not attained satisfactory outcomes. Building on the strategy of freezing the language model, we conduct thorough structural exploration and introduce the Inner-Adaptor Architecture (IAA). Specifically, the architecture incorporates multiple multimodal adaptors at varying depths within the large language model to facilitate direct interaction with the inherently text-oriented transformer layers, thereby enabling the frozen language model to acquire multimodal capabilities. Unlike previous approaches of freezing language models that require large-scale aligned data, our proposed architecture is able to achieve superior performance on small-scale datasets. We conduct extensive experiments to improve the general multimodal capabilities and visual grounding abilities of the MLLM. Our approach remarkably outperforms previous state-of-the-art methods across various vision-language benchmarks without sacrificing performance on NLP tasks. Code and models are available at https://github.com/360CVGroup/Inner-Adaptor-Architecture.'
