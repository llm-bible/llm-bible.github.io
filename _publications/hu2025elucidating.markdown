---
layout: publication
title: 'Mrag: Elucidating The Design Space Of Multi-modal Retrieval-augmented Generation'
authors: Chan-wei Hu, Yueqi Wang, Shuo Xing, Chia-ju Chen, Zhengzhong Tu
conference: "Arxiv"
year: 2025
bibkey: hu2025elucidating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24073'}
tags: ['Agentic', 'RAG', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Vision-Language Models (LVLMs) have made remarkable strides in multimodal tasks such as visual question answering, visual grounding, and complex reasoning. However, they remain limited by static training data, susceptibility to hallucinations, and inability to verify claims against up-to-date, external evidence, compromising their performance in dynamic real-world applications. Retrieval-Augmented Generation (RAG) offers a practical solution to mitigate these challenges by allowing the LVLMs to access large-scale knowledge databases via retrieval mechanisms, thereby grounding model outputs in factual, contextually relevant information. Here in this paper, we conduct the first systematic dissection of the multimodal RAG pipeline for LVLMs, explicitly investigating (1) the retrieval phase: on the modality configurations and retrieval strategies, (2) the re-ranking stage: on strategies to mitigate positional biases and improve the relevance of retrieved evidence, and (3) the generation phase: we further investigate how to best integrate retrieved candidates into the final generation process. Finally, we extend to explore a unified agentic framework that integrates re-ranking and generation through self-reflection, enabling LVLMs to select relevant evidence and suppress irrelevant context dynamically. Our full-stack exploration of RAG for LVLMs yields substantial insights, resulting in an average performance boost of 5% without any fine-tuning.
