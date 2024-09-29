---
layout: publication
title: LMGT Optimizing Exploration-Exploitation Balance in Reinforcement Learning through Language Model Guided Trade-offs
authors: Deng Yongxin, Qiu Xihe, Tan Xiaoyu, Chu Wei, Xu Yinghui
conference: "Arxiv"
year: 2024
bibkey: deng2024lmgt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04744"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The uncertainty inherent in the environmental transition model of Reinforcement Learning (RL) necessitates a careful balance between exploration and exploitation to optimize the use of computational resources for accurately estimating an agents expected reward. Achieving balance in control systems is particularly challenging in scenarios with sparse rewards. However given the extensive prior knowledge available for many environments it is redundant to begin learning from scratch in such settings. To address this we introduce anguage odel uided rade-offs (i.e. ) a novel sample-efficient framework that leverages the comprehensive prior knowledge embedded in Large Language Models (LLMs) and their adeptness at processing non-standard data forms such as wiki tutorials. LMGT proficiently manages the exploration-exploitation trade-off by employing reward shifts guided by LLMs which direct agents exploration endeavors thereby improving sample efficiency. We have thoroughly tested LMGT across various RL tasks and deployed it in industrial-grade RL recommendation systems where it consistently outperforms baseline methods. The results indicate that our framework can significantly reduce the time cost required during the training phase in RL.
