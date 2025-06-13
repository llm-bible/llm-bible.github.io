---
layout: publication
title: 'Fundamental Limitations In Defending LLM Finetuning Apis'
authors: Xander Davies, Eric Winsor, Tomek Korbak, Alexandra Souly, Robert Kirk, Christian Schroeder De Witt, Yarin Gal
conference: "Arxiv"
year: 2025
bibkey: davies2025fundamental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14828"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods']
---
LLM developers have imposed technical interventions to prevent fine-tuning
misuse attacks, attacks where adversaries evade safeguards by fine-tuning the
model using a public API. Previous work has established several successful
attacks against specific fine-tuning API defences. In this work, we show that
defences of fine-tuning APIs that seek to detect individual harmful training or
inference samples ('pointwise' detection) are fundamentally limited in their
ability to prevent fine-tuning attacks. We construct 'pointwise-undetectable'
attacks that repurpose entropy in benign model outputs (e.g. semantic or
syntactic variations) to covertly transmit dangerous knowledge. Our attacks are
composed solely of unsuspicious benign samples that can be collected from the
model before fine-tuning, meaning training and inference samples are all
individually benign and low-perplexity. We test our attacks against the OpenAI
fine-tuning API, finding they succeed in eliciting answers to harmful
multiple-choice questions, and that they evade an enhanced monitoring system we
design that successfully detects other fine-tuning attacks. We encourage the
community to develop defences that tackle the fundamental limitations we
uncover in pointwise fine-tuning API defences.
