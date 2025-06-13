---
layout: publication
title: 'Reward Modeling With Weak Supervision For Language Models'
authors: Ben Hauptvogel, Malte Ostendorff, Georg Rehm, Sebastian Möller
conference: "Arxiv"
year: 2024
bibkey: hauptvogel2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20869"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning']
---
Recent advancements in large language models (LLMs) have led to their
increased application across various tasks, with reinforcement learning from
human feedback (RLHF) being a crucial part of their training to align responses
with user intentions. In the RLHF process, a reward model is trained using
responses preferences determined by human labelers or AI systems, which then
refines the LLM through reinforcement learning. This work introduces weak
supervision as a strategy to extend RLHF datasets and enhance reward model
performance. Weak supervision employs noisy or imprecise data labeling,
reducing reliance on expensive manually labeled data. By analyzing RLHF
datasets to identify heuristics that correlate with response preference, we
wrote simple labeling functions and then calibrated a label model to weakly
annotate unlabeled data. Our evaluation show that while weak supervision
significantly benefits smaller datasets by improving reward model performance,
its effectiveness decreases with larger, originally labeled datasets.
Additionally, using an LLM to generate and then weakly label responses offers a
promising method for extending preference data.
