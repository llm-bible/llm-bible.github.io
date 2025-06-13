---
layout: publication
title: 'M-prometheus: A Suite Of Open Multilingual LLM Judges'
authors: José Pombal, Dongkeun Yoon, Patrick Fernandes, Ian Wu, Seungone Kim, Ricardo Rei, Graham Neubig, André F. T. Martins
conference: "Arxiv"
year: 2025
bibkey: pombal2025m
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04953"}
tags: ['RAG', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
The use of language models for automatically evaluating long-form text
(LLM-as-a-judge) is becoming increasingly common, yet most LLM judges are
optimized exclusively for English, with strategies for enhancing their
multilingual evaluation capabilities remaining largely unexplored in the
current literature. This has created a disparity in the quality of automatic
evaluation methods for non-English languages, ultimately hindering the
development of models with better multilingual capabilities. To bridge this
gap, we introduce M-Prometheus, a suite of open-weight LLM judges ranging from
3B to 14B parameters that can provide both direct assessment and pairwise
comparison feedback on multilingual outputs. M-Prometheus models outperform
state-of-the-art open LLM judges on multilingual reward benchmarks spanning
more than 20 languages, as well as on literary machine translation (MT)
evaluation covering 4 language pairs. Furthermore, M-Prometheus models can be
leveraged at decoding time to significantly improve generated outputs across
all 3 tested languages, showcasing their utility for the development of better
multilingual models. Lastly, through extensive ablations, we identify the key
factors for obtaining an effective multilingual judge, including backbone model
selection and training on natively multilingual feedback data instead of
translated data. We release our models, training dataset, and code.
