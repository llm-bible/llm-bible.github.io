---
layout: publication
title: 'SPARC: Subspace-aware Prompt Adaptation For Robust Continual Learning In Llms'
authors: Dinithi Intel Labs, Oregon Jayasuriya, Sina Intel Labs, Oregon Tayebati, Davide Intel Labs, Oregon Ettori, Ranganath Intel Labs, Oregon Krishnan, Amit Ranjan Intel Labs, Oregon Trivedi
conference: "Arxiv"
year: 2025
bibkey: jayasuriya2025subspace
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02909"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
We propose SPARC, a lightweight continual learning framework for large
language models (LLMs) that enables efficient task adaptation through prompt
tuning in a lower-dimensional space. By leveraging principal component analysis
(PCA), we identify a compact subspace of the training data. Optimizing prompts
in this lower-dimensional space enhances training efficiency, as it focuses
updates on the most relevant features while reducing computational overhead.
Furthermore, since the model's internal structure remains unaltered, the
extensive knowledge gained from pretraining is fully preserved, ensuring that
previously learned information is not compromised during adaptation. Our method
achieves high knowledge retention in both task-incremental and
domain-incremental continual learning setups while fine-tuning only 0.04% of
the model's parameters. Additionally, by integrating LoRA, we enhance
adaptability to computational constraints, allowing for a tradeoff between
accuracy and training cost. Experiments on the SuperGLUE benchmark demonstrate
that our PCA-based prompt tuning combined with LoRA maintains full knowledge
retention while improving accuracy, utilizing only 1% of the model's
parameters. These results establish our approach as a scalable and
resource-efficient solution for continual learning in LLMs.
