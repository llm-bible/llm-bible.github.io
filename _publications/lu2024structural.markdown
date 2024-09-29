---
layout: publication
title: Ovis Structural Embedding Alignment For Multimodal Large Language Model
authors: Lu Shiyin, Li Yang, Chen Qing-guo, Xu Zhao, Luo Weihua, Zhang Kaifu, Ye Han-jia
conference: "Arxiv"
year: 2024
bibkey: lu2024structural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20797"}
  - {name: "Code", url: "https://github.com/AIDC-AI/Ovis"}
tags: ['Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
Current Multimodal Large Language Models (MLLMs) typically integrate a pre-trained LLM with another pre-trained vision transformer through a connector such as an MLP endowing the LLM with visual capabilities. However the misalignment between two embedding strategies in MLLMs -- the structural textual embeddings based on an embedding look-up table and the continuous embeddings generated directly by the vision encoder -- makes challenges for a more seamless fusion of visual and textual information. We propose Ovis a novel MLLM architecture designed to structurally align visual and textual embeddings. Ovis integrates an additional learnable visual embedding table into the visual encoders process. To capture rich visual semantics each image patch indexes the visual embedding table multiple times resulting in a final visual embedding that is a probabilistic combination of the indexed embeddings. This structural approach mirrors the method used for generating textual embeddings. Empirical evaluations on various multimodal benchmarks show that Ovis outperforms open-source MLLMs of similar parameter scales and even surpasses the proprietary model Qwen-VL-Plus overall. These results highlight the potential of Ovis structured visual representation for advancing MLLM architectural design and promoting more effective multimodal learning. Code datasets and models are available at https://github.com/AIDC-AI/Ovis."
