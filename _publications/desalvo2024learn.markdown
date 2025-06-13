---
layout: publication
title: 'Softsrv: Learn To Generate Targeted Synthetic Data'
authors: Giulia Desalvo, Jean-fracois Kagy, Lazaros Karydas, Afshin Rostamizadeh, Sanjiv Kumar
conference: "Arxiv"
year: 2024
bibkey: desalvo2024learn
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.16534'}
tags: ['Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
We present a novel framework, SoftSRV, that is used to generate targeted
synthetic fine-tuning data for improving task-specific model performance. Given
a sample from a target distribution, our proposed framework uses a data-driven
loss minimization approach to steer a frozen large language model (LLM) to
generate synthetic sequences that are similar to those from the target
distribution. SoftSRV provides a practical improvement over common prompt
engineering approaches that rely on human-engineered prompt-templates, which
can be idiosyncratic, labor-intensive to craft, and may need to be specialized
per domain. We empirically evaluate our method against standard baselines
guiding a large LLM to generate synthetic data to fine-tune a smaller language
model on three different domains (coding, math, reasoning). We perform these
evaluations without any particular specialization of the framework to each
domain, emphasizing the generality of our approach. We find that SoftSRV
improves upon typical prompt engineering approaches, generating targeted data
that leads to fine-tuned models with significantly better task-specific
performance. In addition, SoftSRV-generated data better matches the target
distribution according to the MAUVE similarity metric.
