---
layout: publication
title: 'Llms Are Frequency Pattern Learners In Natural Language Inference'
authors: Liang Cheng, Zhaowei Wang, Mark Steedman
conference: "Arxiv"
year: 2025
bibkey: cheng2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21011"}
tags: ['Security', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
While fine-tuning LLMs on NLI corpora improves their inferential performance, the underlying mechanisms driving this improvement remain largely opaque. In this work, we conduct a series of experiments to investigate what LLMs actually learn during fine-tuning. We begin by analyzing predicate frequencies in premises and hypotheses across NLI datasets and identify a consistent frequency bias, where predicates in hypotheses occur more frequently than those in premises for positive instances. To assess the impact of this bias, we evaluate both standard and NLI fine-tuned LLMs on bias-consistent and bias-adversarial cases. We find that LLMs exploit frequency bias for inference and perform poorly on adversarial instances. Furthermore, fine-tuned LLMs exhibit significantly increased reliance on this bias, suggesting that they are learning these frequency patterns from datasets. Finally, we compute the frequencies of hyponyms and their corresponding hypernyms from WordNet, revealing a correlation between frequency bias and textual entailment. These findings help explain why learning frequency patterns can enhance model performance on inference tasks.
