---
layout: publication
title: 'Reasoningrec: Bridging Personalized Recommendations And Human-interpretable Explanations Through LLM Reasoning'
authors: Millennium Bismay, Xiangjue Dong, James Caverlee
conference: "Arxiv"
year: 2024
bibkey: bismay2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23180"}
  - {name: "Code", url: "https://github.com/millenniumbismay/reasoningrec"}
tags: ['RAG', 'Has Code', 'Tools', 'Interpretability and Explainability']
---
This paper presents ReasoningRec, a reasoning-based recommendation framework
that leverages Large Language Models (LLMs) to bridge the gap between
recommendations and human-interpretable explanations. In contrast to
conventional recommendation systems that rely on implicit user-item
interactions, ReasoningRec employs LLMs to model users and items, focusing on
preferences, aversions, and explanatory reasoning. The framework utilizes a
larger LLM to generate synthetic explanations for user preferences,
subsequently used to fine-tune a smaller LLM for enhanced recommendation
accuracy and human-interpretable explanation. Our experimental study
investigates the impact of reasoning and contextual information on personalized
recommendations, revealing that the quality of contextual and personalized data
significantly influences the LLM's capacity to generate plausible explanations.
Empirical evaluations demonstrate that ReasoningRec surpasses state-of-the-art
methods by up to 12.5% in recommendation prediction while concurrently
providing human-intelligible explanations. The code is available here:
https://github.com/millenniumbismay/reasoningrec.
