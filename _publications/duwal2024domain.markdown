---
layout: publication
title: 'Domain-adaptative Continual Learning For Low-resource Tasks: Evaluation On Nepali'
authors: Sharad Duwal, Suraj Prasai, Suresh Manandhar
conference: "Arxiv"
year: 2024
bibkey: duwal2024domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13860"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
Continual learning has emerged as an important research direction due to the
infeasibility of retraining large language models (LLMs) from scratch in the
event of new data availability. Of great interest is the domain-adaptive
pre-training (DAPT) paradigm, which focuses on continually training a
pre-trained language model to adapt it to a domain it was not originally
trained on. In this work, we evaluate the feasibility of DAPT in a low-resource
setting, namely the Nepali language. We use synthetic data to continue training
Llama 3 8B to adapt it to the Nepali language in a 4-bit QLoRA setting. We
evaluate the adapted model on its performance, forgetting, and knowledge
acquisition. We compare the base model and the final model on their Nepali
generation abilities, their performance on popular benchmarks, and run
case-studies to probe their linguistic knowledge in Nepali. We see some
unsurprising forgetting in the final model, but also surprisingly find that
increasing the number of shots during evaluation yields better percent
increases in the final model (as high as 19.29% increase) compared to the base
model (4.98%), suggesting latent retention. We also explore layer-head
self-attention heatmaps to establish dependency resolution abilities of the
final model in Nepali.
