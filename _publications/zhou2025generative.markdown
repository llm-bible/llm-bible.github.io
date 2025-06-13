---
layout: publication
title: 'Generative RLHF-V: Learning Principles From Multi-modal Human Preference'
authors: Jiayi Zhou, Jiaming Ji, Boyuan Chen, Jiapeng Sun, Wenqi Chen, Donghai Hong, Sirui Han, Yike Guo, Yaodong Yang
conference: "Arxiv"
year: 2025
bibkey: zhou2025generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18531"}
  - {name: "Code", url: "https://generative-rlhf-v.github.io"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Training multi-modal large language models (MLLMs) that align with human intentions is a long-term challenge. Traditional score-only reward models for alignment suffer from low accuracy, weak generalization, and poor interpretability, blocking the progress of alignment methods, e.g., reinforcement learning from human feedback (RLHF). Generative reward models (GRMs) leverage MLLMs' intrinsic reasoning capabilities to discriminate pair-wise responses, but their pair-wise paradigm makes it hard to generalize to learnable rewards. We introduce Generative RLHF-V, a novel alignment framework that integrates GRMs with multi-modal RLHF. We propose a two-stage pipeline: \\(\textbf\{multi-modal generative reward modeling from RL\}\\), where RL guides GRMs to actively capture human intention, then predict the correct pair-wise scores; and \\(\textbf\{RL optimization from grouped comparison\}\\), which enhances multi-modal RL scoring precision by grouped responses comparison. Experimental results demonstrate that, besides out-of-distribution generalization of RM discrimination, our framework improves 4 MLLMs' performance across 7 benchmarks by \\(18.1%\\), while the baseline RLHF is only \\(5.3%\\). We further validate that Generative RLHF-V achieves a near-linear improvement with an increasing number of candidate responses. Our code and models can be found at https://generative-rlhf-v.github.io.
