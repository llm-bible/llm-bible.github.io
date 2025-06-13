---
layout: publication
title: 'Think Twice: Enhancing LLM Reasoning By Scaling Multi-round Test-time Thinking'
authors: Xiaoyu Tian, Sitong Zhao, Haotian Wang, Shuaiting Chen, Yunjie Ji, Yiping Peng, Han Zhao, Xiangang Li
conference: "Arxiv"
year: 2025
bibkey: tian2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19855"}
tags: ['Agentic', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Recent advances in large language models (LLMs), such as OpenAI-o1 and
DeepSeek-R1, have demonstrated the effectiveness of test-time scaling, where
extended reasoning processes substantially enhance model performance. Despite
this, current models are constrained by limitations in handling long texts and
reinforcement learning (RL) training efficiency. To address these issues, we
propose a simple yet effective test-time scaling approach Multi-round Thinking.
This method iteratively refines model reasoning by leveraging previous answers
as prompts for subsequent rounds. Extensive experiments across multiple models,
including QwQ-32B and DeepSeek-R1, consistently show performance improvements
on various benchmarks such as AIME 2024, MATH-500, GPQA-diamond, and
LiveCodeBench. For instance, the accuracy of QwQ-32B improved from 80.3% (Round
1) to 82.1% (Round 2) on the AIME 2024 dataset, while DeepSeek-R1 showed a
similar increase from 79.7% to 82.0%. These results confirm that Multi-round
Thinking is a broadly applicable, straightforward approach to achieving stable
enhancements in model performance, underscoring its potential for future
developments in test-time scaling techniques. The key prompt: \{Original
question prompt\} The assistant's previous answer is: <answer> \{last round
answer\} </answer>, and please re-answer.
