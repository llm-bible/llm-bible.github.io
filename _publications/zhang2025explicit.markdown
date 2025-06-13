---
layout: publication
title: 'An Explicit Syllogistic Legal Reasoning Framework For Large Language Models'
authors: Kepu Zhang, Weijie Yu, Zhongxiang Sun, Jun Xu
conference: "Arxiv"
year: 2025
bibkey: zhang2025explicit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04042"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Syllogistic reasoning is crucial for sound legal decision-making, allowing legal professionals to draw logical conclusions by applying general principles to specific case facts. While large language models (LLMs) can answer legal questions, they often struggle with explicit syllogistic reasoning. Their outputs tend to be implicit, unstructured, and consequently, less explainable and trustworthy. To overcome these limitations, we introduce SyLeR, a novel framework designed to enable LLMs to perform explicit syllogistic legal reasoning. SyLeR employs a tree-structured hierarchical retrieval mechanism to synthesize relevant legal statutes and precedents, thereby constructing comprehensive major premises. This is followed by a two-stage fine-tuning process: an initial supervised fine-tuning warm-up establishes a foundational understanding of syllogistic reasoning, while reinforcement learning, guided by a structure-aware reward mechanism, refines the model's capacity to generate diverse, logically sound, and well-structured reasoning paths. We conducted extensive experiments to evaluate SyLeR's performance. Our evaluations spanned diverse dimensions, including both in-domain and cross-domain user groups (legal laypersons and practitioners), multiple languages (Chinese and French), and various LLM backbones (legal-specific and open-domain LLMs). The results consistently demonstrate that SyLeR significantly enhances response accuracy and reliably produces explicit, explainable, and trustworthy legal reasoning.
