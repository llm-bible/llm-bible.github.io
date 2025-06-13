---
layout: publication
title: 'Mllm-guided VLM Fine-tuning With Joint Inference For Zero-shot Composed Image Retrieval'
authors: Rong-cheng Tu, Zhao Jin, Jingyi Liao, Xiao Luo, Yingjie Wang, Li Shen, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: tu2025mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19707"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Existing Zero-Shot Composed Image Retrieval (ZS-CIR) methods typically train adapters that convert reference images into pseudo-text tokens, which are concatenated with the modifying text and processed by frozen text encoders in pretrained VLMs or LLMs. While this design leverages the strengths of large pretrained models, it only supervises the adapter to produce encoder-compatible tokens that loosely preserve visual semantics. Crucially, it does not directly optimize the composed query representation to capture the full intent of the composition or to align with the target semantics, thereby limiting retrieval performance, particularly in cases involving fine-grained or complex visual transformations. To address this problem, we propose MLLM-Guided VLM Fine-Tuning with Joint Inference (MVFT-JI), a novel approach that leverages a pretrained multimodal large language model (MLLM) to construct two complementary training tasks using only unlabeled images: target text retrieval taskand text-to-image retrieval task. By jointly optimizing these tasks, our method enables the VLM to inherently acquire robust compositional retrieval capabilities, supported by the provided theoretical justifications and empirical validation. Furthermore, during inference, we further prompt the MLLM to generate target texts from composed queries and compute retrieval scores by integrating similarities between (i) the composed query and candidate images, and (ii) the MLLM-generated target text and candidate images. This strategy effectively combines the VLM's semantic alignment strengths with the MLLM's reasoning capabilities.
