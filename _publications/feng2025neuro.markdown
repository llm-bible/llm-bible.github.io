---
layout: publication
title: 'A Neuro-inspired Interpretation Of Unlearning In Large Language Models Through Sample-level Unlearning Difficulty'
authors: Xiaohua Feng, Yuyuan Li, Chengye Wang, Junlin Liu, Li Zhang, Chaochao Chen
conference: "Arxiv"
year: 2025
bibkey: feng2025neuro
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06658"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Interpretability and Explainability', 'Attention Mechanism']
---
Driven by privacy protection laws and regulations, unlearning in Large
Language Models (LLMs) is gaining increasing attention. However, current
research often neglects the interpretability of the unlearning process,
particularly concerning sample-level unlearning difficulty. Existing studies
typically assume a uniform unlearning difficulty across samples. This
simplification risks attributing the performance of unlearning algorithms to
sample selection rather than the algorithm's design, potentially steering the
development of LLM unlearning in the wrong direction. Thus, we investigate the
relationship between LLM unlearning and sample characteristics, with a focus on
unlearning difficulty. Drawing inspiration from neuroscience, we propose a
Memory Removal Difficulty (\\(\mathrm\{MRD\}\\)) metric to quantify sample-level
unlearning difficulty. Using \\(\mathrm\{MRD\}\\), we analyze the characteristics of
hard-to-unlearn versus easy-to-unlearn samples. Furthermore, we propose an
\\(\mathrm\{MRD\}\\)-based weighted sampling method to optimize existing unlearning
algorithms, which prioritizes easily forgettable samples, thereby improving
unlearning efficiency and effectiveness. We validate the proposed metric and
method using public benchmarks and datasets, with results confirming its
effectiveness.
