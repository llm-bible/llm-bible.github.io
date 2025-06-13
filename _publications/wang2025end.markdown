---
layout: publication
title: 'End-to-end Vision Tokenizer Tuning'
authors: Wenxuan Wang, Fan Zhang, Yufeng Cui, Haiwen Diao, Zhuoyan Luo, Huchuan Lu, Jing Liu, Xinlong Wang
conference: "Arxiv"
year: 2025
bibkey: wang2025end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10562"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Tokenization', 'RAG', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Applications']
---
Existing vision tokenization isolates the optimization of vision tokenizers from downstream training, implicitly assuming the visual tokens can generalize well across various tasks, e.g., image generation and visual question answering. The vision tokenizer optimized for low-level reconstruction is agnostic to downstream tasks requiring varied representations and semantics. This decoupled paradigm introduces a critical misalignment: The loss of the vision tokenization can be the representation bottleneck for target tasks. For example, errors in tokenizing text in a given image lead to poor results when recognizing or generating them. To address this, we propose ETT, an end-to-end vision tokenizer tuning approach that enables joint optimization between vision tokenization and target autoregressive tasks. Unlike prior autoregressive models that use only discrete indices from a frozen vision tokenizer, ETT leverages the visual embeddings of the tokenizer codebook, and optimizes the vision tokenizers end-to-end with both reconstruction and caption objectives. ETT can be seamlessly integrated into existing training pipelines with minimal architecture modifications. Our ETT is simple to implement and integrate, without the need to adjust the original codebooks or architectures of the employed large language models. Extensive experiments demonstrate that our proposed end-to-end vision tokenizer tuning unlocks significant performance gains, i.e., 2-6% for multimodal understanding and visual generation tasks compared to frozen tokenizer baselines, while preserving the original reconstruction capability. We hope this very simple and strong method can empower multimodal foundation models besides image generation and understanding.
