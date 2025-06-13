---
layout: publication
title: 'Mixture Of Insightful Experts (mote): The Synergy Of Thought Chains And Expert Mixtures In Self-alignment'
authors: Zhili Liu, Yunhao Gou, Kai Chen, Lanqing Hong, Jiahui Gao, Fei Mi, Yu Zhang, Zhenguo Li, Xin Jiang, Qun Liu, James T. Kwok
conference: "Arxiv"
year: 2024
bibkey: liu2024mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.00557'}
tags: ['Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI']
---
As the capabilities of large language models (LLMs) continue to expand, aligning these models with human values remains a significant challenge. Recent studies show that reasoning abilities contribute significantly to model safety, while integrating Mixture-of-Experts (MoE) architectures can further enhance alignment. In this work, we address a fundamental question: How to effectively incorporate reasoning abilities and MoE architectures into self-alignment process in LLMs? We propose Mixture of insighTful Experts (MoTE), a novel framework that synergistically combines reasoning chains and expert mixtures to improve self-alignments. From a data perspective, MoTE employs a structured reasoning chain comprising four key stages: Question Analysis, Answer Guidance, Safe Answer, and Safety Checking. This approach enhances safety through multi-step reasoning and proves effective even for smaller and less powerful LLMs (e.g., 7B models). From an architectural perspective, MoTE adopts a multi-LoRA framework with step-level routing, where each expert is dedicated to a specific reasoning step. This design eliminates the need for balance losses, ensures stable training, and supports adaptive inference lengths. Experimental results demonstrate that MoTE significantly improves model safety, jailbreak resistance, and over-refusal capabilities, achieving performance comparable to OpenAI's state-of-the-art o1 model.
