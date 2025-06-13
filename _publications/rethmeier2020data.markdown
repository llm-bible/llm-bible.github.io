---
layout: publication
title: 'Data-efficient Pretraining Via Contrastive Self-supervision'
authors: Nils Rethmeier, Isabelle Augenstein
conference: "Arxiv"
year: 2020
bibkey: rethmeier2020data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.01061"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fairness', 'Few-Shot', 'Model Architecture', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'BERT', 'Fine-Tuning']
---
For natural language processing `text-to-text' tasks, the prevailing
approaches heavily rely on pretraining large self-supervised models on
increasingly larger `task-external' data. Transfer learning from high-resource
pretraining works well, but research has focused on settings with very large
data and compute requirements, while the potential of efficient low-resource
learning, without large `task-external' pretraining, remains under-explored. In
this work, we evaluate against three core challenges for resource efficient
learning. Namely, we analyze: (1) pretraining data (\\(X\\)) efficiency; (2) zero
to few-shot label (\\(Y\\)) efficiency; and (3) long-tail generalization, since
long-tail preservation has been linked to algorithmic fairness and because data
in the tail is limited by definition. To address these challenges, we propose a
data and compute efficient self-supervised, contrastive text encoder,
pretrained on 60MB of `task-internal' text data, and compare it to RoBERTa,
which was pretrained on 160GB of `task-external' text. We find our method
outperforms RoBERTa, while pretraining and fine-tuning in a 1/5th of RoBERTa's
fine-tuning time.
