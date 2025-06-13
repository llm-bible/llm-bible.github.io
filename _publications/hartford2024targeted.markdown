---
layout: publication
title: 'Spectrum: Targeted Training On Signal To Noise Ratio'
authors: Eric Hartford, Lucas Atkins, Fernando Fernandes Neto, David Golchinfar
conference: "Arxiv"
year: 2024
bibkey: hartford2024targeted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06623"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning']
---
Efficiently post-training large language models remains a challenging task
due to the vast computational resources required. We present Spectrum, a method
that accelerates LLM training by selectively targeting layer modules based on
their signal-to-noise ratio (SNR), and freezing the remaining modules. Our
approach, which utilizes an algorithm to compute module SNRs prior to training,
has shown to effectively match the performance of full fine-tuning while
reducing GPU memory usage. Experiments comparing Spectrum to existing methods
such as QLoRA demonstrate its effectiveness in terms of model quality and VRAM
efficiency in distributed environments.
