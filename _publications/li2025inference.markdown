---
layout: publication
title: 'Fairsteer: Inference Time Debiasing For Llms With Dynamic Activation Steering'
authors: Yichen Li, Zhiting Fan, Ruizhe Chen, Xiaotang Gai, Luqi Gong, Yan Zhang, Zuozhu Liu
conference: "Arxiv"
year: 2025
bibkey: li2025inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14492"}
tags: ['Training Techniques', 'Fairness', 'Tools', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) are prone to capturing biases from training
corpus, leading to potential negative social impacts. Existing prompt-based
debiasing methods exhibit instability due to their sensitivity to prompt
changes, while fine-tuning-based techniques incur substantial computational
overhead and catastrophic forgetting. In this paper, we propose FairSteer, a
novel inference-time debiasing framework without requiring customized prompt
design or model retraining. Motivated by the linear representation hypothesis,
our preliminary investigation demonstrates that fairness-related features can
be encoded into separable directions in the hidden activation space. FairSteer
operates in three steps: biased activation detection, debiasing steering vector
(DSV) computation, and dynamic activation steering. Specifically, it first
trains a lightweight linear classifier to detect bias signatures in
activations, and then computes DSVs as intervention directions derived from
small contrastive prompt pairs. Subsequently, it performs debiasing by
adjusting activations with DSVs in the inference stage. Comprehensive
evaluation with six LLMs demonstrates the superiority of FairSteer across
question-answering, counterfactual input evaluation and open-ended text
generation tasks. Code will be released.
