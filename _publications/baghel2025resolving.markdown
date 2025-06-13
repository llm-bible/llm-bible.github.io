---
layout: publication
title: 'Resolving Underedit & Overedit With Iterative & Neighbor-assisted Model Editing'
authors: Bhiman Kumar Baghel, Scott M. Jordan, Zheyuan Ryan Shi, Xiang Lorraine Li
conference: "Arxiv"
year: 2025
bibkey: baghel2025resolving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11895"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
Large Language Models (LLMs) are used in various downstream language tasks,
making it crucial to keep their knowledge up-to-date, but both retraining and
fine-tuning the model can be costly. Model editing offers an efficient and
effective alternative by a single update to only a key subset of model
parameters. While being efficient, these methods are not perfect. Sometimes
knowledge edits are unsuccessful, i.e., UnderEdit, or the edit contaminated
neighboring knowledge that should remain unchanged, i.e., OverEdit. To address
these limitations, we propose iterative model editing, based on our hypothesis
that a single parameter update is often insufficient, to mitigate UnderEdit,
and neighbor-assisted model editing, which incorporates neighboring knowledge
during editing to minimize OverEdit. Extensive experiments demonstrate that our
methods effectively reduce UnderEdit up to 38 percentage points and OverEdit up
to 6 percentage points across multiple model editing algorithms, LLMs, and
benchmark datasets.
