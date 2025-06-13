---
layout: publication
title: 'Exploring The Robustness Of Task-oriented Dialogue Systems For Colloquial German Varieties'
authors: Ekaterina Artemova, Verena Blaschke, Barbara Plank
conference: "Arxiv"
year: 2024
bibkey: artemova2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02078"}
tags: ['Fine-Tuning', 'Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Mainstream cross-lingual task-oriented dialogue (ToD) systems leverage the
transfer learning paradigm by training a joint model for intent recognition and
slot-filling in English and applying it, zero-shot, to other languages. We
address a gap in prior research, which often overlooked the transfer to
lower-resource colloquial varieties due to limited test data. Inspired by prior
work on English varieties, we craft and manually evaluate perturbation rules
that transform German sentences into colloquial forms and use them to
synthesize test sets in four ToD datasets. Our perturbation rules cover 18
distinct language phenomena, enabling us to explore the impact of each
perturbation on slot and intent performance. Using these new datasets, we
conduct an experimental evaluation across six different transformers. Here, we
demonstrate that when applied to colloquial varieties, ToD systems maintain
their intent recognition performance, losing 6% (4.62 percentage points) in
accuracy on average. However, they exhibit a significant drop in slot
detection, with a decrease of 31% (21 percentage points) in slot F1 score. Our
findings are further supported by a transfer experiment from Standard American
English to synthetic Urban African American Vernacular English.
