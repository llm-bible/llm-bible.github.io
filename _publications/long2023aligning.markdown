---
layout: publication
title: 'Aligning Large Language Models With Human Opinions Through Persona Selection And Value--belief--norm Reasoning'
authors: Do Xuan Long, Kenji Kawaguchi, Min-yen Kan, Nancy F. Chen
conference: "Arxiv"
year: 2023
bibkey: long2023aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08385"}
tags: ['Prompting', 'Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Reasoning and predicting human opinions with large language models (LLMs) is
essential yet challenging. Current methods employ role-playing with personae
but face two major issues: LLMs are sensitive to even a single irrelevant
persona, skewing predictions by up to 30%, and LLMs fail to reason
strategically over personae. We propose Chain-of-Opinion (COO), a simple
four-step solution modeling which and how to reason with personae, inspired by
the Value--Belief--Norm (VBN) theory. COO differentiates between explicit
personae (demographics and ideology) and implicit personae (historical
opinions), involves: (1) filtering irrelevant attributes from explicit
personae, (2) ranking implicit personae into a preferential list for selecting
top-k, (3) applying novel VBN reasoning to extract user environmental and
personal value, belief, and norm variables for accurate and reliable
predictions, and (4) iterating VBN reasoning with progressively larger lists of
implicit personae to handle potential persona insufficiency. COO efficiently
achieves new state-of-the-art opinion prediction via prompting with only 5
inference calls, improving prior techniques by up to 4%. Notably, fine-tuning
LMs with COO data results in significantly better opinion-aligned models, by up
to 23%.
