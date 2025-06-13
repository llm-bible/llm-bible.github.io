---
layout: publication
title: 'Learn To Think: Bootstrapping LLM Reasoning Capability Through Graph Representation Learning'
authors: Hang Gao, Chenhao Zhang, Tie Wang, Junsuo Zhao, Fengge Wu, Changwen Zheng, Huaping Liu
conference: "Arxiv"
year: 2025
bibkey: gao2025learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06321"}
  - {name: "Code", url: "https://github.com/zch65458525/L2T"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have achieved remarkable success across various domains. However, they still face significant challenges, including high computational costs for training and limitations in solving complex reasoning problems. Although existing methods have extended the reasoning capabilities of LLMs through structured paradigms, these approaches often rely on task-specific prompts and predefined reasoning processes, which constrain their flexibility and generalizability. To address these limitations, we propose a novel framework that leverages graph learning to enable more flexible and adaptive reasoning capabilities for LLMs. Specifically, this approach models the reasoning process of a problem as a graph and employs LLM-based graph learning to guide the adaptive generation of each reasoning step. To further enhance the adaptability of the model, we introduce a Graph Neural Network (GNN) module to perform representation learning on the generated reasoning process, enabling real-time adjustments to both the model and the prompt. Experimental results demonstrate that this method significantly improves reasoning performance across multiple tasks without requiring additional training or task-specific prompt design. Code can be found in https://github.com/zch65458525/L2T.
