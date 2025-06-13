---
layout: publication
title: 'Context-aware Assistant Selection For Improved Inference Acceleration With Large Language Models'
authors: Jerry Huang, Prasanna Parthasarathi, Mehdi Rezagholizadeh, Sarath Chandar
conference: "Arxiv"
year: 2024
bibkey: huang2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.08470'}
tags: ['RAG', 'Interpretability', 'Training Techniques']
---
Despite their widespread adoption, large language models (LLMs) remain
prohibitive to use under resource constraints, with their ever growing sizes
only increasing the barrier for use. One noted issue is the high latency
associated with auto-regressive generation, rendering large LLMs use dependent
on advanced computing infrastructure. Assisted decoding, where a smaller draft
model guides a larger target model's generation, has helped alleviate this, but
remains dependent on alignment between the two models. Thus if the draft model
is insufficiently capable on some domain relative to the target model,
performance can degrade. Alternatively, one can leverage multiple draft models
to better cover the expertise of the target, but when multiple black-box draft
models are available, selecting an assistant without details about its
construction can be difficult. To better understand this decision making
problem, we observe it as a contextual bandit, where a policy must choose a
draft model based on a context. We show that even without prior knowledge of
the draft models, creating an offline dataset from only outputs of independent
draft/target models and training a policy over the alignment of these outputs
can accelerate performance on multiple domains provided the candidates are
effective. Further results show this to hold on various settings with multiple
assisted decoding candidates, highlighting its flexibility and the advantageous
role that such decision making can play.
