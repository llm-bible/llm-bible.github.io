---
layout: publication
title: 'Generalizing Trust: Weak-to-strong Trustworthiness In Language Models'
authors: Martin Pawelczyk, Lillian Sun, Zhenting Qi, Aounon Kumar, Himabindu Lakkaraju
conference: "Arxiv"
year: 2024
bibkey: pawelczyk2024generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00418"}
tags: ['Security', 'Training Techniques', 'Fairness', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
The rapid proliferation of generative AI, especially large language models,
has led to their integration into a variety of applications. A key phenomenon
known as weak-to-strong generalization - where a strong model trained on a weak
model's outputs surpasses the weak model in task performance - has gained
significant attention. Yet, whether critical trustworthiness properties such as
robustness, fairness, and privacy can generalize similarly remains an open
question. In this work, we study this question by examining if a stronger model
can inherit trustworthiness properties when fine-tuned on a weaker model's
outputs, a process we term weak-to-strong trustworthiness generalization. To
address this, we introduce two foundational training strategies: 1) Weak
Trustworthiness Finetuning (Weak TFT), which leverages trustworthiness
regularization during the fine-tuning of the weak model, and 2) Weak and
Weak-to-Strong Trustworthiness Finetuning (Weak+WTS TFT), which extends
regularization to both weak and strong models. Our experimental evaluation on
real-world datasets reveals that while some trustworthiness properties, such as
fairness, adversarial, and OOD robustness, show significant improvement in
transfer when both models were regularized, others like privacy do not exhibit
signs of weak-to-strong trustworthiness. As the first study to explore
trustworthiness generalization via weak-to-strong generalization, our work
provides valuable insights into the potential and limitations of weak-to-strong
generalization.
