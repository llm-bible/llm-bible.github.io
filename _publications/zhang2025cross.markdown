---
layout: publication
title: 'Cross From Left To Right Brain: Adaptive Text Dreamer For Vision-and-language Navigation'
authors: Pingrui Zhang, Yifei Su, Pengyuan Wu, Dong An, Li Zhang, Zhigang Wang, Dong Wang, Yan Ding, Bin Zhao, Xuelong Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20897"}
  - {name: "Code", url: "https://github.com/zhangpingrui/Adaptive-Text-Dreamer}{here"}
tags: ['Agentic', 'Has Code', 'Model Architecture']
---
Vision-and-Language Navigation (VLN) requires the agent to navigate by following natural instructions under partial observability, making it difficult to align perception with language. Recent methods mitigate this by imagining future scenes, yet they rely on vision-based synthesis, leading to high computational cost and redundant details. To this end, we propose to adaptively imagine key environmental semantics via \textit\{language\} form, enabling a more reliable and efficient strategy. Specifically, we introduce a novel Adaptive Text Dreamer (ATD), a dual-branch self-guided imagination policy built upon a large language model (LLM). ATD is designed with a human-like left-right brain architecture, where the left brain focuses on logical integration, and the right brain is responsible for imaginative prediction of future scenes. To achieve this, we fine-tune only the Q-former within both brains to efficiently activate domain-specific knowledge in the LLM, enabling dynamic updates of logical reasoning and imagination during navigation. Furthermore, we introduce a cross-interaction mechanism to regularize the imagined outputs and inject them into a navigation expert module, allowing ATD to jointly exploit both the reasoning capacity of the LLM and the expertise of the navigation model. We conduct extensive experiments on the R2R benchmark, where ATD achieves state-of-the-art performance with fewer parameters. The code is \href\{https://github.com/zhangpingrui/Adaptive-Text-Dreamer\}\{here\}.
