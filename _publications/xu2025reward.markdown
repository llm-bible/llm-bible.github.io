---
layout: publication
title: 'Reward Models Identify Consistency, Not Causality'
authors: Yuhui Xu, Hanze Dong, Lei Wang, Caiming Xiong, Junnan Li
conference: "Arxiv"
year: 2025
bibkey: xu2025reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14619"}
tags: ['Model Architecture', 'Reinforcement Learning']
---
Reward models (RMs) play a crucial role in aligning large language models
(LLMs) with human preferences and enhancing reasoning quality. Traditionally,
RMs are trained to rank candidate outputs based on their correctness and
coherence. However, in this work, we present several surprising findings that
challenge common assumptions about RM behavior. Our analysis reveals that
state-of-the-art reward models prioritize structural consistency over causal
correctness. Specifically, removing the problem statement has minimal impact on
reward scores, whereas altering numerical values or disrupting the reasoning
flow significantly affects RM outputs. Furthermore, RMs exhibit a strong
dependence on complete reasoning trajectories truncated or incomplete steps
lead to significant variations in reward assignments, indicating that RMs
primarily rely on learned reasoning patterns rather than explicit problem
comprehension. These findings hold across multiple architectures, datasets, and
tasks, leading to three key insights: (1) RMs primarily assess coherence rather
than true reasoning quality; (2) The role of explicit problem comprehension in
reward assignment is overstated; (3) Current RMs may be more effective at
ranking responses than verifying logical validity. Our results suggest a
fundamental limitation in existing reward modeling approaches, emphasizing the
need for a shift toward causality-aware reward models that go beyond
consistency-driven evaluation.
