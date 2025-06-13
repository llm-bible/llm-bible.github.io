---
layout: publication
title: 'Beyond Guilt: Legal Judgment Prediction With Trichotomous Reasoning'
authors: Kepu Zhang, Haoyue Yang, Xu Tang, Weijie Yu, Jun Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14588"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
In legal practice, judges apply the trichotomous dogmatics of criminal law,
sequentially assessing the elements of the offense, unlawfulness, and
culpability to determine whether an individual's conduct constitutes a crime.
Although current legal large language models (LLMs) show promising accuracy in
judgment prediction, they lack trichotomous reasoning capabilities due to the
absence of an appropriate benchmark dataset, preventing them from predicting
innocent outcomes. As a result, every input is automatically assigned a charge,
limiting their practical utility in legal contexts. To bridge this gap, we
introduce LJPIV, the first benchmark dataset for Legal Judgment Prediction with
Innocent Verdicts. Adhering to the trichotomous dogmatics, we extend three
widely-used legal datasets through LLM-based augmentation and manual
verification. Our experiments with state-of-the-art legal LLMs and novel
strategies that integrate trichotomous reasoning into zero-shot prompting and
fine-tuning reveal: (1) current legal LLMs have significant room for
improvement, with even the best models achieving an F1 score of less than 0.3
on LJPIV; and (2) our strategies notably enhance both in-domain and
cross-domain judgment prediction accuracy, especially for cases resulting in an
innocent verdict.
