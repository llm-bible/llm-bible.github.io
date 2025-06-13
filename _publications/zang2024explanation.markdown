---
layout: publication
title: 'Explanation Based Bias Decoupling Regularization For Natural Language Inference'
authors: Jianxiang Zang, Hui Liu
conference: "Arxiv"
year: 2024
bibkey: zang2024explanation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13390"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability']
---
The robustness of Transformer-based Natural Language Inference encoders is
frequently compromised as they tend to rely more on dataset biases than on the
intended task-relevant features. Recent studies have attempted to mitigate this
by reducing the weight of biased samples during the training process. However,
these debiasing methods primarily focus on identifying which samples are biased
without explicitly determining the biased components within each case. This
limitation restricts those methods' capability in out-of-distribution
inference. To address this issue, we aim to train models to adopt the logic
humans use in explaining causality. We propose a simple, comprehensive, and
interpretable method: Explanation based Bias Decoupling Regularization
(EBD-Reg). EBD-Reg employs human explanations as criteria, guiding the encoder
to establish a tripartite parallel supervision of Distinguishing, Decoupling
and Aligning. This method enables encoders to identify and focus on keywords
that represent the task-relevant features during inference, while discarding
the residual elements acting as biases. Empirical evidence underscores that
EBD-Reg effectively guides various Transformer-based encoders to decouple
biases through a human-centric lens, significantly surpassing other methods in
terms of out-of-distribution inference capabilities.
