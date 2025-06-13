---
layout: publication
title: 'Hardtests: Synthesizing High-quality Test Cases For LLM Coding'
authors: Zhongmou He, Yee Man Choi, Kexun Zhang, Jiabao Ji, Junting Zhou, Dejia Xu, Ivan Bercovich, Aidan Zhang, Lei Li
conference: "Arxiv"
year: 2025
bibkey: he2025synthesizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24098"}
  - {name: "Code", url: "https://leililab.github.io/HardTests/"}
tags: ['Agentic', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Verifiers play a crucial role in large language model (LLM) reasoning, needed by post-training techniques such as reinforcement learning. However, reliable verifiers are hard to get for difficult coding problems, because a well-disguised wrong solution may only be detected by carefully human-written edge cases that are difficult to synthesize. To address this issue, we propose HARDTESTGEN, a pipeline for high-quality test synthesis using LLMs. With this pipeline, we curate a comprehensive competitive programming dataset HARDTESTS with 47k problems and synthetic high-quality tests. Compared with existing tests, HARDTESTGEN tests demonstrate precision that is 11.3 percentage points higher and recall that is 17.5 percentage points higher when evaluating LLM-generated code. For harder problems, the improvement in precision can be as large as 40 points. HARDTESTS also proves to be more effective for model training, measured by downstream code generation performance. We will open-source our dataset and synthesis pipeline at https://leililab.github.io/HardTests/.
