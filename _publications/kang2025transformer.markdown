---
layout: publication
title: 'Modrwkv: Transformer Multimodality In Linear Time'
authors: Jiale Kang, Ziyin Yue, Qingyu Yin, Jiang Rui, Weile Li, Zening Lu, Zhouran Ji
conference: "Arxiv"
year: 2025
bibkey: kang2025transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14505"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Currently, most multimodal studies are based on large language models (LLMs) with quadratic-complexity Transformer architectures. While linear models like RNNs enjoy low inference costs, their application has been largely limited to the text-only modality. This work explores the capabilities of modern RNN architectures in multimodal contexts. We propose ModRWKV-a decoupled multimodal framework built upon the RWKV7 architecture as its LLM backbone-which achieves multi-source information fusion through dynamically adaptable heterogeneous modality encoders. We designed the multimodal modules in ModRWKV with an extremely lightweight architecture and, through extensive experiments, identified a configuration that achieves an optimal balance between performance and computational efficiency. ModRWKV leverages the pretrained weights of the RWKV7 LLM for initialization, which significantly accelerates multimodal training. Comparative experiments with different pretrained checkpoints further demonstrate that such initialization plays a crucial role in enhancing the model's ability to understand multimodal signals. Supported by extensive experiments, we conclude that modern RNN architectures present a viable alternative to Transformers in the domain of multimodal large language models (MLLMs). Furthermore, we identify the optimal configuration of the ModRWKV architecture through systematic exploration.
