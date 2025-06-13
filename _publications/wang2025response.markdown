---
layout: publication
title: 'Response Uncertainty And Probe Modeling: Two Sides Of The Same Coin In LLM Interpretability?'
authors: Yongjie Wang, Yibo Wang, Xin Zhou, Zhiqi Shen
conference: "Arxiv"
year: 2025
bibkey: wang2025response
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18575"}
tags: ['Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Interpretability', 'Training Techniques']
---
Probing techniques have shown promise in revealing how LLMs encode human-interpretable concepts, particularly when applied to curated datasets. However, the factors governing a dataset's suitability for effective probe training are not well-understood. This study hypothesizes that probe performance on such datasets reflects characteristics of both the LLM's generated responses and its internal feature space. Through quantitative analysis of probe performance and LLM response uncertainty across a series of tasks, we find a strong correlation: improved probe performance consistently corresponds to a reduction in response uncertainty, and vice versa. Subsequently, we delve deeper into this correlation through the lens of feature importance analysis. Our findings indicate that high LLM response variance is associated with a larger set of important features, which poses a greater challenge for probe models and often results in diminished performance. Moreover, leveraging the insights from response uncertainty analysis, we are able to identify concrete examples where LLM representations align with human knowledge across diverse domains, offering additional evidence of interpretable reasoning in LLMs.
