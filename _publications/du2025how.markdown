---
layout: publication
title: 'How Post-training Reshapes Llms: A Mechanistic View On Knowledge, Truthfulness, Refusal, And Confidence'
authors: Hongzhe Du, Weikai Li, Min Cai, Karim Saraipour, Zimin Zhang, Himabindu Lakkaraju, Yizhou Sun, Shichang Zhang
conference: "Arxiv"
year: 2025
bibkey: du2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02904"}
tags: ['RAG', 'Training Techniques', 'Interpretability and Explainability']
---
Post-training is essential for the success of large language models (LLMs),
transforming pre-trained base models into more useful and aligned post-trained
models. While plenty of works have studied post-training algorithms and
evaluated post-training models by their outputs, it remains understudied how
post-training reshapes LLMs internally. In this paper, we compare base and
post-trained LLMs mechanistically from four perspectives to better understand
post-training effects. Our findings across model families and datasets reveal
that: (1) Post-training does not change the factual knowledge storage
locations, and it adapts knowledge representations from the base model while
developing new knowledge representations; (2) Both truthfulness and refusal can
be represented by linear vectors in the hidden representation space. The
truthfulness direction is highly similar between the base and post-trained
model, and it is effectively transferable for interventions; (3) The refusal
direction is different between the base and post-trained models, and it shows
limited forward transferability; (4) Differences in confidence between the base
and post-trained models cannot be attributed to entropy neurons. Our study
provides insights into the fundamental mechanisms preserved and altered during
post-training, facilitates downstream tasks like model steering, and could
potentially benefit future research in interpretability and LLM post-training.
