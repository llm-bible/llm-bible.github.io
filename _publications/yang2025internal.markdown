---
layout: publication
title: 'Internal Chain-of-thought: Empirical Evidence For Layer-wise Subtask Scheduling In Llms'
authors: Zhipeng Yang, Junzhuo Li, Siyu Xia, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: yang2025internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14530"}
tags: ['Ethics and Bias', 'Interpretability', 'Reinforcement Learning']
---
We show that large language models (LLMs) exhibit an \\(\textit\{internal chain-of-thought\}\\): they sequentially decompose and execute composite tasks layer-by-layer. Two claims ground our study: (i) distinct subtasks are learned at different network depths, and (ii) these subtasks are executed sequentially across layers. On a benchmark of 15 two-step composite tasks, we employ layer-from context-masking and propose a novel cross-task patching method, confirming (i). To examine claim (ii), we apply LogitLens to decode hidden states, revealing a consistent layerwise execution pattern. We further replicate our analysis on the real-world \\(\text\{TRACE\}\\) benchmark, observing the same stepwise dynamics. Together, our results enhance LLMs transparency by showing their capacity to internally plan and execute subtasks (or instructions), opening avenues for fine-grained, instruction-level activation steering.
