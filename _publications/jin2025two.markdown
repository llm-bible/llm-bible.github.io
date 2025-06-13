---
layout: publication
title: 'Two Heads Are Better Than One: Test-time Scaling Of Multi-agent Collaborative Reasoning'
authors: Can Jin, Hongwu Peng, Qixin Zhang, Yujin Tang, Dimitris N. Metaxas, Tong Che
conference: "Arxiv"
year: 2025
bibkey: jin2025two
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09772'}
  - {name: "Code", url: 'https://github.com/jincan333/MAS-TTS'}
tags: ['Agentic', 'Has Code', 'Agent', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Multi-agent systems (MAS) built on large language models (LLMs) offer a
promising path toward solving complex, real-world tasks that single-agent
systems often struggle to manage. While recent advancements in test-time
scaling (TTS) have significantly improved single-agent performance on
challenging reasoning tasks, how to effectively scale collaboration and
reasoning in MAS remains an open question. In this work, we introduce an
adaptive multi-agent framework designed to enhance collaborative reasoning
through both model-level training and system-level coordination. We construct
M500, a high-quality dataset containing 500 multi-agent collaborative reasoning
traces, and fine-tune Qwen2.5-32B-Instruct on this dataset to produce M1-32B, a
model optimized for multi-agent collaboration. To further enable adaptive
reasoning, we propose a novel CEO agent that dynamically manages the discussion
process, guiding agent collaboration and adjusting reasoning depth for more
effective problem-solving. Evaluated in an open-source MAS across a range of
tasks-including general understanding, mathematical reasoning, and coding-our
system significantly outperforms strong baselines. For instance, M1-32B
achieves 12% improvement on GPQA-Diamond, 41% on AIME2024, and 10% on
MBPP-Sanitized, matching the performance of state-of-the-art models like
DeepSeek-R1 on some tasks. These results highlight the importance of both
learned collaboration and adaptive coordination in scaling multi-agent
reasoning. Code is available at https://github.com/jincan333/MAS-TTS
