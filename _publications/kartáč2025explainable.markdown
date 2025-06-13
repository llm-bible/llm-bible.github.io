---
layout: publication
title: 'Openlgauge: An Explainable Metric For NLG Evaluation With Open-weights Llms'
authors: Ivan Kartáč, Mateusz Lango, Ondřej Dušek
conference: "Arxiv"
year: 2025
bibkey: kartáč2025explainable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11858"}
tags: ['Training Techniques', 'Interpretability and Explainability']
---
Large Language Models (LLMs) have demonstrated great potential as evaluators
of NLG systems, allowing for high-quality, reference-free, and multi-aspect
assessments. However, existing LLM-based metrics suffer from two major
drawbacks: reliance on proprietary models to generate training data or perform
evaluations, and a lack of fine-grained, explanatory feedback. In this paper,
we introduce OpeNLGauge, a fully open-source, reference-free NLG evaluation
metric that provides accurate explanations based on error spans. OpeNLGauge is
available as a two-stage ensemble of larger open-weight LLMs, or as a small
fine-tuned evaluation model, with confirmed generalizability to unseen tasks,
domains and aspects. Our extensive meta-evaluation shows that OpeNLGauge
achieves competitive correlation with human judgments, outperforming
state-of-the-art models on certain tasks while maintaining full reproducibility
and providing explanations more than twice as accurate.
