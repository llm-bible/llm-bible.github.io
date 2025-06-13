---
layout: publication
title: 'A Rose By Any Other Name: Llm-generated Explanations Are Good Proxies For Human Explanations To Collect Label Distributions On NLI'
authors: Beiduo Chen, Siyao Peng, Anna Korhonen, Barbara Plank
conference: "Arxiv"
year: 2024
bibkey: chen2024rose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13942"}
tags: ['Interpretability and Explainability']
---
Disagreement in human labeling is ubiquitous, and can be captured in human judgment distributions (HJDs). Recent research has shown that explanations provide valuable information for understanding human label variation (HLV) and large language models (LLMs) can approximate HJD from a few human-provided label-explanation pairs. However, collecting explanations for every label is still time-consuming. This paper examines whether LLMs can be used to replace humans in generating explanations for approximating HJD. Specifically, we use LLMs as annotators to generate model explanations for a few given human labels. We test ways to obtain and combine these label-explanations with the goal to approximate human judgment distributions. We further compare the resulting human with model-generated explanations, and test automatic and human explanation selection. Our experiments show that LLM explanations are promising for NLI: to estimate HJDs, generated explanations yield comparable results to human's when provided with human labels. Importantly, our results generalize from datasets with human explanations to i) datasets where they are not available and ii) challenging out-of-distribution test sets.
