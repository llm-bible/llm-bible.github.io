---
layout: publication
title: 'Almost Surely Safe Alignment Of Large Language Models At Inference-time'
authors: Xiaotong Ji, Shyam Sundhar Ramesh, Matthieu Zimmer, Ilija Bogunovic, Jun Wang, Haitham Bou Ammar
conference: "Arxiv"
year: 2025
bibkey: ji2025almost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01208"}
tags: ['Responsible AI', 'Ethics and Bias', 'Reinforcement Learning']
---
Even highly capable large language models (LLMs) can produce biased or unsafe
responses, and alignment techniques, such as RLHF, aimed at mitigating this
issue, are expensive and prone to overfitting as they retrain the LLM. This
paper introduces a novel inference-time alignment approach that ensures LLMs
generate safe responses almost surely, i.e., with a probability approaching
one. We achieve this by framing the safe generation of inference-time responses
as a constrained Markov decision process within the LLM's latent space.
Crucially, we augment a safety state that tracks the evolution of safety
constraints and enables us to demonstrate formal safety guarantees upon solving
the MDP in the latent space. Building on this foundation, we propose
InferenceGuard, a practical implementation that safely aligns LLMs without
modifying the model weights. Empirically, we demonstrate InferenceGuard
effectively balances safety and task performance, outperforming existing
inference-time alignment methods in generating safe and aligned responses.
