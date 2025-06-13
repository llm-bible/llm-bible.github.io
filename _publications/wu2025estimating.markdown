---
layout: publication
title: 'Estimating LLM Consistency: A User Baseline Vs Surrogate Metrics'
authors: Xiaoyuan Wu, Weiran Lin, Omer Akgul, Lujo Bauer
conference: "Arxiv"
year: 2025
bibkey: wu2025estimating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23799"}
tags: ['RAG', 'Prompting']
---
Large language models (LLMs) are prone to hallucinations and sensitive to prompt perturbations, often resulting in inconsistent or unreliable generated text. Different methods have been proposed to mitigate such hallucinations and fragility -- one of them being measuring the consistency (the model's confidence in the response, or likelihood of generating a similar response when resampled) of LLM responses. In previous work, measuring consistency often relied on the probability of a response appearing within a pool of resampled responses, or internal states or logits of responses. However, it is not yet clear how well these approaches approximate how humans perceive the consistency of LLM responses. We performed a user study (n=2,976) and found current methods typically do not approximate users' perceptions of LLM consistency very well. We propose a logit-based ensemble method for estimating LLM consistency, and we show that this method matches the performance of the best-performing existing metric in estimating human ratings of LLM consistency. Our results suggest that methods of estimating LLM consistency without human evaluation are sufficiently imperfect that we suggest evaluation with human input be more broadly used.
