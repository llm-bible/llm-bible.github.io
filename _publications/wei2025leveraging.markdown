---
layout: publication
title: 'Alignrag: Leveraging Critique Learning For Evidence-sensitive Retrieval-augmented Reasoning'
authors: Jiaqi Wei, Hao Zhou, Xiang Zhang, Di Zhang, Zijie Qiu, Wei Wei, Jinzhe Li, Wanli Ouyang, Siqi Sun
conference: "Arxiv"
year: 2025
bibkey: wei2025leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14858'}
tags: ['RAG', 'Security', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias']
---
Retrieval-augmented generation (RAG) has become a widely adopted paradigm for enabling knowledge-grounded large language models (LLMs). However, standard RAG pipelines often fail to ensure that model reasoning remains consistent with the evidence retrieved, leading to factual inconsistencies or unsupported conclusions. In this work, we reinterpret RAG as Retrieval-Augmented Reasoning and identify a central but underexplored problem: \textit\{Reasoning Misalignment\}-the divergence between an LLM's internal reasoning trajectory and the evidential constraints provided by retrieval. To address this issue, we propose \textsc\{AlignRAG\}, a novel iterative framework grounded in Critique-Driven Alignment (CDA). At the heart of \textsc\{AlignRAG\} lies a \textit\{contrastive critique synthesis\} mechanism that generates retrieval-sensitive critiques while mitigating self-bias. This mechanism trains a dedicated retrieval-augmented \textit\{Critic Language Model (CLM)\} using labeled critiques that distinguish between evidence-aligned and misaligned reasoning. Alignment signals for supervision are obtained through self-supervised or externally guided labeling strategies. The resulting CLM is explicitly optimized for evidence sensitivity, enabling it to detect and revise reasoning errors during inference without relying solely on self-generated feedback. Empirical evaluations show that our 8B-parameter CLM improves performance over the Self-Refine baseline by 12.1% on out-of-domain tasks and outperforms a standard 72B-parameter CLM by 2.2%, while remaining compatible with existing RAG architectures as a plug-and-play module. Overall, AlignRAG offers a principled solution for aligning model reasoning with retrieved evidence, substantially improving the factual reliability and robustness of RAG systems.
