---
layout: publication
title: 'From Reasoning To Generalization: Knowledge-augmented Llms For ARC Benchmark'
authors: Chao Lei, Nir Lipovetzky, Krista A. Ehinger, Yanchuan Chang
conference: "Arxiv"
year: 2025
bibkey: lei2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17482"}
tags: ['Applications']
---
Recent reasoning-oriented LLMs have demonstrated strong performance on challenging tasks such as mathematics and science examinations. However, core cognitive faculties of human intelligence, such as abstract reasoning and generalization, remain underexplored. To address this, we evaluate recent reasoning-oriented LLMs on the Abstraction and Reasoning Corpus (ARC) benchmark, which explicitly demands both faculties. We formulate ARC as a program synthesis task and propose nine candidate solvers. Experimental results show that repeated-sampling planning-aided code generation (RSPC) achieves the highest test accuracy and demonstrates consistent generalization across most LLMs. To further improve performance, we introduce an ARC solver, Knowledge Augmentation for Abstract Reasoning (KAAR), which encodes core knowledge priors within an ontology that classifies priors into three hierarchical levels based on their dependencies. KAAR progressively expands LLM reasoning capacity by gradually augmenting priors at each level, and invokes RSPC to generate candidate solutions after each augmentation stage. This stage-wise reasoning reduces interference from irrelevant priors and improves LLM performance. Empirical results show that KAAR maintains strong generalization and consistently outperforms non-augmented RSPC across all evaluated LLMs, achieving around 5% absolute gains and up to 64.52% relative improvement. Despite these achievements, ARC remains a challenging benchmark for reasoning-oriented LLMs, highlighting future avenues of progress in LLMs.
