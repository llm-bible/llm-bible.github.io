---
layout: publication
title: 'Model Utility Law: Evaluating Llms Beyond Performance Through Mechanism Interpretable Metric'
authors: Yixin Cao, Jiahao Ying, Yaoning Wang, Xipeng Qiu, Xuanjing Huang, Yugang Jiang
conference: "Arxiv"
year: 2025
bibkey: cao2025model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07440"}
  - {name: "Code", url: "https://github.com/ALEX-nlp/MUI-Eva"}
tags: ['Tools', 'Applications', 'Interpretability and Explainability', 'Training Techniques', 'Has Code']
---
Large Language Models (LLMs) have become indispensable across academia, industry, and daily applications, yet current evaluation methods struggle to keep pace with their rapid development. One core challenge of evaluation in the large language model (LLM) era is the generalization issue: how to infer a model's near-unbounded abilities from inevitably bounded benchmarks. We address this challenge by proposing Model Utilization Index (MUI), a mechanism interpretability enhanced metric that complements traditional performance scores. MUI quantifies the effort a model expends on a task, defined as the proportion of activated neurons or features during inference. Intuitively, a truly capable model should achieve higher performance with lower effort. Extensive experiments across popular LLMs reveal a consistent inverse logarithmic relationship between MUI and performance, which we formulate as the Utility Law. From this law we derive four practical corollaries that (i) guide training diagnostics, (ii) expose data contamination issue, (iii) enable fairer model comparisons, and (iv) design model-specific dataset diversity. Our code can be found at https://github.com/ALEX-nlp/MUI-Eva.
