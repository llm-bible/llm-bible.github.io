---
layout: publication
title: Agent-simt Agent-assisted Simultaneous Machine Translation With Large Language Models
authors: Guo Shoutao, Zhang Shaolei, Ma Zhengrui, Zhang Min, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: guo2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06910"}
tags: ['Agentic', 'Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Simultaneous Machine Translation (SiMT) generates target translations while reading the source sentence. It relies on a policy to determine the optimal timing for reading sentences and generating translations. Existing SiMT methods generally adopt the traditional Transformer architecture which concurrently determines the policy and generates translations. While they excel at determining policies their translation performance is suboptimal. Conversely Large Language Models (LLMs) trained on extensive corpora possess superior generation capabilities but it is difficult for them to acquire translation policy through the training methods of SiMT. Therefore we introduce Agent-SiMT a framework combining the strengths of LLMs and traditional SiMT methods. Agent-SiMT contains the policy-decision agent and the translation agent. The policy-decision agent is managed by a SiMT model which determines the translation policy using partial source sentence and translation. The translation agent leveraging an LLM generates translation based on the partial source sentence. The two agents collaborate to accomplish SiMT. Experiments demonstrate that Agent-SiMT attains state-of-the-art performance.
