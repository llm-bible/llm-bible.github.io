---
layout: publication
title: 'Training-free Reasoning And Reflection In Mllms'
authors: Hongchen Wei, Zhenzhong Chen
conference: "Arxiv"
year: 2025
bibkey: wei2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16151"}
  - {name: "Code", url: "http://iip.whu.edu.cn/frank/index.html"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'GPT', 'Has Code', 'Attention Mechanism']
---
Recent advances in Reasoning LLMs (e.g., DeepSeek-R1 and OpenAI-o1) have showcased impressive reasoning capabilities via reinforcement learning. However, extending these capabilities to Multimodal LLMs (MLLMs) is hampered by the prohibitive costs of retraining and the scarcity of high-quality, verifiable multimodal reasoning datasets. This paper introduces FRANK Model, a training-FRee ANd r1-liKe MLLM that imbues off-the-shelf MLLMs with reasoning and reflection abilities, without any gradient updates or extra supervision. Our key insight is to decouple perception and reasoning across MLLM decoder layers. Specifically, we observe that compared to the deeper decoder layers, the shallow decoder layers allocate more attention to visual tokens, while the deeper decoder layers concentrate on textual semantics. This observation motivates a hierarchical weight merging approach that combines a visual-pretrained MLLM with a reasoning-specialized LLM. To this end, we propose a layer-wise, Taylor-derived closed-form fusion mechanism that integrates reasoning capacity into deep decoder layers while preserving visual grounding in shallow decoder layers. Extensive experiments on challenging multimodal reasoning benchmarks demonstrate the effectiveness of our approach. On the MMMU benchmark, our model FRANK-38B achieves an accuracy of 69.2, outperforming the strongest baseline InternVL2.5-38B by +5.3, and even surpasses the proprietary GPT-4o model. Our project homepage is at: http://iip.whu.edu.cn/frank/index.html
