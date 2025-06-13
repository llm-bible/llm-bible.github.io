---
layout: publication
title: 'Towards Faithful Natural Language Explanations: A Study Using Activation Patching In Large Language Models'
authors: Wei Jie Yeo, Ranjan Satapathy, Erik Cambria
conference: "Arxiv"
year: 2024
bibkey: yeo2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14155'}
  - {name: "Code", url: 'https://github.com/wj210/Causal-Faithfulness'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Interpretability and Explainability']
---
Large Language Models (LLMs) are capable of generating persuasive Natural
Language Explanations (NLEs) to justify their answers. However, the
faithfulness of these explanations should not be readily trusted at face value.
Recent studies have proposed various methods to measure the faithfulness of
NLEs, typically by inserting perturbations at the explanation or feature level.
We argue that these approaches are neither comprehensive nor correctly designed
according to the established definition of faithfulness. Moreover, we highlight
the risks of grounding faithfulness findings on out-of-distribution samples. In
this work, we leverage a causal mediation technique called activation patching,
to measure the faithfulness of an explanation towards supporting the explained
answer. Our proposed metric, Causal Faithfulness quantifies the consistency of
causal attributions between explanations and the corresponding model outputs as
the indicator of faithfulness. We experimented across models varying from 2B to
27B parameters and found that models that underwent alignment tuning tend to
produce more faithful and plausible explanations. We find that Causal
Faithfulness is a promising improvement over existing faithfulness tests by
taking into account the model's internal computations and avoiding out of
distribution concerns that could otherwise undermine the validity of
faithfulness assessments. We release the code in
\url\{https://github.com/wj210/Causal-Faithfulness\}
