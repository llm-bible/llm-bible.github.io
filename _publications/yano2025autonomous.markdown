---
layout: publication
title: 'Lamdagent: An Autonomous Framework For Post-training Pipeline Optimization Via LLM Agents'
authors: Taro Yano, Yoichi Ishibashi, Masafumi Oyamada
conference: "Arxiv"
year: 2025
bibkey: yano2025autonomous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21963"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs) have demonstrated exceptional performance across a wide range of tasks. To further tailor LLMs to specific domains or applications, post-training techniques such as Supervised Fine-Tuning (SFT), Preference Learning, and model merging are commonly employed. While each of these methods has been extensively studied in isolation, the automated construction of complete post-training pipelines remains an underexplored area. Existing approaches typically rely on manual design or focus narrowly on optimizing individual components, such as data ordering or merging strategies. In this work, we introduce LaMDAgent (short for Language Model Developing Agent), a novel framework that autonomously constructs and optimizes full post-training pipelines through the use of LLM-based agents. LaMDAgent systematically explores diverse model generation techniques, datasets, and hyperparameter configurations, leveraging task-based feedback to discover high-performing pipelines with minimal human intervention. Our experiments show that LaMDAgent improves tool-use accuracy by 9.0 points while preserving instruction-following capabilities. Moreover, it uncovers effective post-training strategies that are often overlooked by conventional human-driven exploration. We further analyze the impact of data and model size scaling to reduce computational costs on the exploration, finding that model size scalings introduces new challenges, whereas scaling data size enables cost-effective pipeline discovery.
