---
layout: publication
title: 'Longdpo: Unlock Better Long-form Generation Abilities For Llms Via Critique-augmented Stepwise Information'
authors: Bowen Ping, Jiali Zeng, Fandong Meng, Shuo Wang, Jie Zhou, Shanghang Zhang
conference: "Arxiv"
year: 2025
bibkey: ping2025unlock
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02095"}
tags: ['Model Architecture', 'Applications', 'GPT', 'Reinforcement Learning']
---
Long-form generation is crucial for academic writing papers and repo-level code generation. Despite this, current models, including GPT-4o, still exhibit unsatisfactory performance. Existing methods that utilize preference learning with outcome supervision often fail to provide detailed feedback for extended contexts. This shortcoming can lead to content that does not fully satisfy query requirements, resulting in issues like length deviations, and diminished quality. In this paper, we propose enhancing long-form generation by incorporating process supervision. We employ Monte Carlo Tree Search to gather stepwise preference pairs, utilizing a global memory pool to maintain consistency. To address the issue of suboptimal candidate selection, we integrate external critiques to refine and improve the quality of the preference pairs. Finally, we apply step-level DPO using the collected stepwise preference pairs. Experimental results show that our method improves length and quality on long-form generation benchmarks, with almost lossless performance on general benchmarks across various model backbones.
