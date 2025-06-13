---
layout: publication
title: 'Dyepack: Provably Flagging Test Set Contamination In Llms Using Backdoors'
authors: Yize Cheng, Wenxiao Wang, Mazda Moayeri, Soheil Feizi
conference: "Arxiv"
year: 2025
bibkey: cheng2025provably
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23001'}
tags: ['RAG', 'Security', 'Training Techniques', 'Tools', 'Ethics and Bias', 'Interpretability']
---
Open benchmarks are essential for evaluating and advancing large language models, offering reproducibility and transparency. However, their accessibility makes them likely targets of test set contamination. In this work, we introduce DyePack, a framework that leverages backdoor attacks to identify models that used benchmark test sets during training, without requiring access to the loss, logits, or any internal details of the model. Like how banks mix dye packs with their money to mark robbers, DyePack mixes backdoor samples with the test data to flag models that trained on it. We propose a principled design incorporating multiple backdoors with stochastic targets, enabling exact false positive rate (FPR) computation when flagging every model. This provably prevents false accusations while providing strong evidence for every detected case of contamination. We evaluate DyePack on five models across three datasets, covering both multiple-choice and open-ended generation tasks. For multiple-choice questions, it successfully detects all contaminated models with guaranteed FPRs as low as 0.000073% on MMLU-Pro and 0.000017% on Big-Bench-Hard using eight backdoors. For open-ended generation tasks, it generalizes well and identifies all contaminated models on Alpaca with a guaranteed false positive rate of just 0.127% using six backdoors.
