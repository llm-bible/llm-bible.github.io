---
layout: publication
title: 'Quantified Task Misalignment To Inform PEFT: An Exploration Of Domain Generalization And Catastrophic Forgetting In CLIP'
authors: Niss Laura, Vogt-lowell Kevin, Tsiligkaridis Theodoros
conference: "Arxiv"
year: 2024
bibkey: niss2024quantified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09613"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Foundations models are presented as generalists that often perform well over
a myriad of tasks. Fine-tuning these models, even on limited data, provides an
additional boost in task-specific performance but often at the cost of their
wider generalization, an effect termed catastrophic forgetting. In this paper,
we analyze the relation between task difficulty in the CLIP model and the
performance of several simple parameter-efficient fine-tuning methods through
the lens of domain generalization and catastrophic forgetting. We provide
evidence that the silhouette score of the zero-shot image and text embeddings
is a better measure of task difficulty than the average cosine similarity of
correct image/label embeddings, and discuss observable relationships between
task difficulty, fine-tuning method, domain generalization, and catastrophic
forgetting. Additionally, the averaged results across tasks and performance
measures demonstrate that a simplified method that trains only a subset of
attention weights, which we call A-CLIP, yields a balance between domain
generalization and catastrophic forgetting.
