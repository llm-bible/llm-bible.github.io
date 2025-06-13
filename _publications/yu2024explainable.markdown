---
layout: publication
title: 'Explainable CTR Prediction Via LLM Reasoning'
authors: Xiaohan Yu, Li Zhang, Chong Chen
conference: "Arxiv"
year: 2024
bibkey: yu2024explainable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02588"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability']
---
Recommendation Systems have become integral to modern user experiences, but
lack transparency in their decision-making processes. Existing explainable
recommendation methods are hindered by reliance on a post-hoc paradigm, wherein
explanation generators are trained independently of the underlying recommender
models. This paradigm necessitates substantial human effort in data
construction and raises concerns about explanation reliability. In this paper,
we present ExpCTR, a novel framework that integrates large language model based
explanation generation directly into the CTR prediction process. Inspired by
recent advances in reinforcement learning, we employ two carefully designed
reward mechanisms, LC alignment, which ensures explanations reflect user
intentions, and IC alignment, which maintains consistency with traditional
ID-based CTR models. Our approach incorporates an efficient training paradigm
with LoRA and a three-stage iterative process. ExpCTR circumvents the need for
extensive explanation datasets while fostering synergy between CTR prediction
and explanation generation. Experimental results demonstrate that ExpCTR
significantly enhances both recommendation accuracy and interpretability across
three real-world datasets.
