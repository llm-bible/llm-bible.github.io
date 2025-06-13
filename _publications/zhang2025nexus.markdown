---
layout: publication
title: 'Nexus-gen: A Unified Model For Image Understanding, Generation, And Editing'
authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yuze Zhao, Weiyi Lu, Zhipeng Di, Yixuan Xu, Yingda Chen, Yu Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025nexus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21356"}
  - {name: "Code", url: "https://github.com/modelscope/Nexus-Gen.git"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Merging', 'GPT', 'Pretraining Methods', 'Has Code']
---
Unified multimodal large language models (MLLMs) aim to integrate multimodal
understanding and generation abilities through a single framework. Despite
their versatility, existing open-source unified models exhibit performance gaps
against domain-specific architectures. To bridge this gap, we present
Nexus-Gen, a unified model that synergizes the language reasoning capabilities
of LLMs with the image synthesis power of diffusion models. To align the
embedding space of the LLM and diffusion model, we conduct a dual-phase
alignment training process. (1) The autoregressive LLM learns to predict image
embeddings conditioned on multimodal inputs, while (2) the vision decoder is
trained to reconstruct high-fidelity images from these embeddings. During
training the LLM, we identified a critical discrepancy between the
autoregressive paradigm's training and inference phases, where error
accumulation in continuous embedding space severely degrades generation
quality. To avoid this issue, we introduce a prefilled autoregression strategy
that prefills input sequence with position-embedded special tokens instead of
continuous embeddings. Through dual-phase training, Nexus-Gen has developed the
integrated capability to comprehensively address the image understanding,
generation and editing tasks. All models, datasets, and codes are published at
https://github.com/modelscope/Nexus-Gen.git to facilitate further advancements
across the field.
