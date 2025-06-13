---
layout: publication
title: 'Interpretable Language Modeling Via Induction-head Ngram Models'
authors: Eunji Kim, Sriya Mantena, Weiwei Yang, Chandan Singh, Sungroh Yoon, Jianfeng Gao
conference: "Arxiv"
year: 2024
bibkey: kim2024interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00066'}
  - {name: "Code", url: 'https://github.com/ejkim47/induction-gram'}
tags: ['Has Code', 'Language Modeling', 'Interpretability and Explainability', 'Efficiency and Optimization']
---
Recent large language models (LLMs) have excelled across a wide range of
tasks, but their use in high-stakes and compute-limited settings has
intensified the demand for interpretability and efficiency. We address this
need by proposing Induction-head ngram models (Induction-Gram), a method that
builds an efficient, interpretable LM by bolstering modern ngram models with a
hand-engineered "induction head". This induction head uses a custom neural
similarity metric to efficiently search the model's input context for potential
next-word completions. This process enables Induction-Gram to provide
ngram-level grounding for each generated token. Moreover, experiments show that
this simple method significantly improves next-word prediction over baseline
interpretable models (up to 26%p) and can be used to speed up LLM inference for
large models through speculative decoding. We further study Induction-Gram in a
natural-language neuroscience setting, where the goal is to predict the next
fMRI response in a sequence. It again provides a significant improvement over
interpretable models (20% relative increase in the correlation of predicted
fMRI responses), potentially enabling deeper scientific investigation of
language selectivity in the brain. The code is available at
https://github.com/ejkim47/induction-gram.
