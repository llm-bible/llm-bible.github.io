---
layout: publication
title: 'Skip-thinking: Chunk-wise Chain-of-thought Distillation Enable Smaller Language Models To Reason Better And Faster'
authors: Xiao Chen, Sihang Zhou, Ke Liang, Xiaoyu Sun, Xinwang Liu
conference: "Arxiv"
year: 2025
bibkey: chen2025skip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18642"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Distillation']
---
Chain-of-thought (CoT) distillation allows a large language model (LLM) to guide a small language model (SLM) in reasoning tasks. Existing methods train the SLM to learn the long rationale in one iteration, resulting in two issues: 1) Long rationales lead to a large token-level batch size during training, making gradients of core reasoning tokens (i.e., the token will directly affect the correctness of subsequent reasoning) over-smoothed as they contribute a tiny fraction of the rationale. As a result, the SLM converges to sharp minima where it fails to grasp the reasoning logic. 2) The response is slow, as the SLM must generate a long rationale before reaching the answer. Therefore, we propose chunk-wise training (CWT), which uses a heuristic search to divide the rationale into internal semantically coherent chunks and focuses SLM on learning from only one chunk per iteration. In this way, CWT naturally isolates non-reasoning chunks that do not involve the core reasoning token (e.g., summary and transitional chunks) from the SLM learning for reasoning chunks, making the fraction of the core reasoning token increase in the corresponding iteration. Based on CWT, skip-thinking training (STT) is proposed. STT makes the SLM automatically skip non-reasoning medium chunks to reach the answer, improving reasoning speed while maintaining accuracy. We validate our approach on a variety of SLMs and multiple reasoning tasks.
