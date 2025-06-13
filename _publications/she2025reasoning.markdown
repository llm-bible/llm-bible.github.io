---
layout: publication
title: 'Hawkeye:efficient Reasoning With Model Collaboration'
authors: Jianshu She, Zhuohao Li, Zhemin Huang, Qi Li, Peiran Xu, Haonan Li, Qirong Ho
conference: "Arxiv"
year: 2025
bibkey: she2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00424'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Chain-of-Thought (CoT) reasoning has demonstrated remarkable effectiveness in
enhancing the reasoning abilities of large language models (LLMs). However, its
efficiency remains a challenge due to the generation of excessive intermediate
reasoning tokens, which introduce semantic redundancy and overly detailed
reasoning steps. Moreover, computational expense and latency are significant
concerns, as the cost scales with the number of output tokens, including those
intermediate steps. In this work, we observe that most CoT tokens are
unnecessary, and retaining only a small portion of them is sufficient for
producing high-quality responses. Inspired by this, we propose HAWKEYE, a novel
post-training and inference framework where a large model produces concise CoT
instructions to guide a smaller model in response generation. HAWKEYE
quantifies redundancy in CoT reasoning and distills high-density information
via reinforcement learning. By leveraging these concise CoTs, HAWKEYE is able
to expand responses while reducing token usage and computational cost
significantly. Our evaluation shows that HAWKEYE can achieve comparable
response quality using only 35% of the full CoTs, while improving clarity,
coherence, and conciseness by approximately 10%. Furthermore, HAWKEYE can
accelerate end-to-end reasoning by up to 3.4x on complex math tasks while
reducing inference cost by up to 60%. HAWKEYE will be open-sourced and the
models will be available soon.
