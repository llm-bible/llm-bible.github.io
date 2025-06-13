---
layout: publication
title: 'MEOW: Memory Supervised LLM Unlearning Via Inverted Facts'
authors: Tianle Gu, Kexin Huang, Ruilin Luo, Yuanqi Yao, Yujiu Yang, Yan Teng, Yingchun Wang
conference: "Arxiv"
year: 2024
bibkey: gu2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11844"}
tags: ['Training Techniques', 'Security', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Large Language Models (LLMs) can memorize sensitive information, raising
concerns about potential misuse. LLM Unlearning, a post-hoc approach to remove
this information from trained LLMs, offers a promising solution to mitigate
these risks. However, previous practices face three key challenges: 1. Utility:
successful unlearning often causes catastrophic collapse on unrelated tasks. 2.
Efficiency: many methods either involve adding similarly sized models, which
slows down unlearning or inference, or require retain data that are difficult
to obtain. 3. Robustness: even effective methods may still leak data via
extraction techniques. To address these challenges, we propose MEOW, a simple
yet effective gradient descent-based unlearning method. Specifically, we use an
offline LLM to generate a set of inverted facts. Then, we design a new metric,
MEMO, to quantify memorization in LLMs. Finally, based on the signals provided
by MEMO, we select the most appropriate set of inverted facts and finetune the
model based on them. We evaluate MEOW on the commonly used unlearn benchmark,
ToFU, with Llama2-7B-Chat and Phi-1.5B, and test it on both NLU and NLG tasks.
Results demonstrate significant improvement of MEOW in forget quality without
substantial loss in model utility. Meanwhile, MEOW does not exhibit significant
degradation in NLU or NLG capabilities, and there is even a slight improvement
in NLU performance.
