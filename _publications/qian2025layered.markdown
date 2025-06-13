---
layout: publication
title: 'Layered Unlearning For Adversarial Relearning'
authors: Timothy Qian, Vinith Suriyakumar, Ashia Wilson, Dylan Hadfield-menell
conference: "Arxiv"
year: 2025
bibkey: qian2025layered
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.09500"}
tags: ['Fine-Tuning', 'Interpretability and Explainability', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Our goal is to understand how post-training methods, such as fine-tuning, alignment, and unlearning, modify language model behavior and representations. We are particularly interested in the brittle nature of these modifications that makes them easy to bypass through prompt engineering or relearning. Recent results suggest that post-training induces shallow context-dependent ``circuits'' that suppress specific response patterns. This could be one explanation for the brittleness of post-training. To test this hypothesis, we design an unlearning algorithm, Layered Unlearning (LU), that creates distinct inhibitory mechanisms for a growing subset of the data. By unlearning the first \\(i\\) folds while retaining the remaining \\(k - i\\) at the \\(i\\)th of \\(k\\) stages, LU limits the ability of relearning on a subset of data to recover the full dataset. We evaluate LU through a combination of synthetic and large language model (LLM) experiments. We find that LU improves robustness to adversarial relearning for several different unlearning methods. Our results contribute to the state-of-the-art of machine unlearning and provide insight into the effect of post-training updates.
