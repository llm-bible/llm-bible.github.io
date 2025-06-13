---
layout: publication
title: 'Sugar-coated Poison: Benign Generation Unlocks LLM Jailbreaking'
authors: Yu-hang Wu, Yu-jie Xiong, Hao Zhang, Jia-chen Zhang, Zheng Zhou
conference: "Arxiv"
year: 2025
bibkey: wu2025sugar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05652"}
tags: ['Responsible AI', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Security', 'Prompting']
---
With the increasingly deep integration of large language models (LLMs) across diverse domains, the effectiveness of their safety mechanisms is encountering severe challenges. Currently, jailbreak attacks based on prompt engineering have become a major safety threat. However, existing methods primarily rely on black-box manipulation of prompt templates, resulting in poor interpretability and limited generalization. To break through the bottleneck, this study first introduces the concept of Defense Threshold Decay (DTD), revealing the potential safety impact caused by LLMs' benign generation: as benign content generation in LLMs increases, the model's focus on input instructions progressively diminishes. Building on this insight, we propose the Sugar-Coated Poison (SCP) attack paradigm, which uses a "semantic reversal" strategy to craft benign inputs that are opposite in meaning to malicious intent. This strategy induces the models to generate extensive benign content, thereby enabling adversarial reasoning to bypass safety mechanisms. Experiments show that SCP outperforms existing baselines. Remarkably, it achieves an average attack success rate of 87.23% across six LLMs. For defense, we propose Part-of-Speech Defense (POSD), leveraging verb-noun dependencies for syntactic analysis to enhance safety of LLMs while preserving their generalization ability.
