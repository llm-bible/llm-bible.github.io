---
layout: publication
title: 'From Large To Super-tiny: End-to-end Optimization For Cost-efficient Llms'
authors: Jiliang Ni, Jiachen Pu, Zhongyi Yang, Kun Zhou, Hui Wang, Xiaoliang Xiao, Dakui Wang, Xin Li, Jingfeng Luo, Conggang Hu
conference: "Arxiv"
year: 2025
bibkey: ni2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13471'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Quantization', 'Fine-Tuning', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have significantly advanced artificial intelligence by optimizing traditional Natural Language Processing (NLP) workflows, facilitating their integration into various systems. Many such NLP systems, including ours, directly incorporate LLMs. However, this approach either results in expensive costs or yields suboptimal performance after fine-tuning. In this paper, we introduce a three-stage cost-efficient end-to-end LLM deployment pipeline, comprising prototyping, knowledge transfer, and model compression, to effectively tackle the cost-performance dilemma in LLM-based frameworks. Its high cost-efficiency is manifested not only in simplifying system complexity and producing super-tiny online models with enhanced performance and reduced costs in the results, but also in addressing development cycle constraints, the lack of extensive high-quality data, and limited computational resources during the project development process. In the first stage, we construct an optimal performance prototype system by transforming complex tasks into a function call-based LLM-driven pipeline, which serves as a teacher model to generate high-quality data. In the second stage, we combine techniques like rejection sampling fine-tuning, reinforcement learning, and knowledge distillation to transfer knowledge to 0.5B student models, delivering effective performance at minimal cost. In the final stage, we further compress models to 0.4B via quantization and pruning, achieving ultra-low latency and cost. Extensive experimental results and the framework's modular design suggest cross-domain capabilities and potential applicability in other NLP areas.
