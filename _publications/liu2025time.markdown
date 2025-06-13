---
layout: publication
title: 'Time-r1: Towards Comprehensive Temporal Reasoning In Llms'
authors: Zijia Liu, Peixuan Han, Haofei Yu, Haoru Li, Jiaxuan You
conference: "Arxiv"
year: 2025
bibkey: liu2025time
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13508'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) demonstrate impressive capabilities but lack robust temporal intelligence, struggling to integrate reasoning about the past with predictions and plausible generations of the future. Meanwhile, existing methods typically target isolated temporal skills, such as question answering about past events or basic forecasting, and exhibit poor generalization, particularly when dealing with events beyond their knowledge cutoff or requiring creative foresight. To address these limitations, we introduce \textit\{Time-R1\}, the first framework to endow a moderate-sized (3B-parameter) LLM with comprehensive temporal abilities: understanding, prediction, and creative generation. Our approach features a novel three-stage development path; the first two constitute a \textit\{reinforcement learning (RL) curriculum\} driven by a meticulously designed dynamic rule-based reward system. This framework progressively builds (1) foundational temporal understanding and logical event-time mappings from historical data, (2) future event prediction skills for events beyond its knowledge cutoff, and finally (3) enables remarkable generalization to creative future scenario generation without any fine-tuning. Strikingly, experiments demonstrate that Time-R1 outperforms models over 200 times larger, including the state-of-the-art 671B DeepSeek-R1, on highly challenging future event prediction and creative scenario generation benchmarks. This work provides strong evidence that thoughtfully engineered, progressive RL fine-tuning allows smaller, efficient models to achieve superior temporal performance, offering a practical and scalable path towards truly time-aware AI. To foster further research, we also release \textit\{Time-Bench\}, a large-scale multi-task temporal reasoning dataset derived from 10 years of news data, and our series of \textit\{Time-R1\} checkpoints.
