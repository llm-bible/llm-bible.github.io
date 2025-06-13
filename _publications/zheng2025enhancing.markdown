---
layout: publication
title: 'Enhancing LLM Reliability Via Explicit Knowledge Boundary Modeling'
authors: Hang Zheng, Hongshen Xu, Yuncong Liu, Lu Chen, Pascale Fung, Kai Yu
conference: "Arxiv"
year: 2025
bibkey: zheng2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02233"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools']
---
Large language models (LLMs) frequently hallucinate due to misaligned
self-awareness, generating erroneous outputs when addressing queries beyond
their knowledge boundaries. While existing approaches mitigate hallucinations
via uncertainty estimation or query rejection, they suffer from computational
inefficiency or sacrificed helpfulness. To address these issues, we propose the
Explicit Knowledge Boundary Modeling (EKBM) framework, integrating fast and
slow reasoning systems to harmonize reliability and usability. The framework
first employs a fast-thinking model to generate confidence-labeled responses,
enabling immediate use of high-confidence outputs. For uncertain predictions, a
slow refinement model conducts targeted reasoning to improve accuracy. To align
model behavior with our proposed object, we propose a hybrid training pipeline,
enhancing self-awareness without degrading task performance. Evaluations on
dialogue state tracking tasks demonstrate that EKBM achieves superior model
reliability over uncertainty-based baselines. Further analysis reveals that
refinement substantially boosts accuracy while maintaining low computational
overhead. Our work establishes a scalable paradigm for advancing LLM
reliability and balancing accuracy and practical utility in error-sensitive
applications.
