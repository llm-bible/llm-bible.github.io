---
layout: publication
title: 'Speech-based Slot Filling Using Large Language Models'
authors: Sun Guangzhi, Feng Shutong, Jiang Dongcheng, Zhang Chao, Gašić Milica, Woodland Philip C.
conference: "Arxiv"
year: 2023
bibkey: sun2023speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07418"}
tags: ['Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
Recently, advancements in large language models (LLMs) have shown an
unprecedented ability across various language tasks. This paper investigates
the potential application of LLMs to slot filling with noisy ASR
transcriptions, via both in-context learning and task-specific fine-tuning.
Dedicated prompt designs and fine-tuning approaches are proposed to improve the
robustness of LLMs for slot filling with noisy ASR transcriptions. Moreover, a
linearised knowledge injection (LKI) scheme is also proposed to integrate
dynamic external knowledge into LLMs. Experiments were performed on SLURP to
quantify the performance of LLMs, including GPT-3.5-turbo, GPT-4, LLaMA-13B and
Vicuna-13B (v1.1 and v1.5) with different ASR error rates. The use of the
proposed fine-tuning together with the LKI scheme for LLaMA-13B achieved an
8.3% absolute SLU-F1 improvement compared to the strong Flan-T5-base baseline
system on a limited data setup.
