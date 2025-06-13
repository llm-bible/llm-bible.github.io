---
layout: publication
title: 'From TOWER To SPIRE: Adding The Speech Modality To A Text-only LLM'
authors: Kshitij Ambilduke, Ben Peters, Sonal Sannigrahi, Anil Keshwani, Tsz Kin Lam, Bruno Martins, Marcely Zanon Boito, André F. T. Martins
conference: "Arxiv"
year: 2025
bibkey: ambilduke2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10620'}
tags: ['Pre-Training', 'Training Techniques']
---
Large language models (LLMs) have shown remarkable performance and
generalization capabilities across multiple languages and tasks, making them
very attractive targets for multi-modality integration (e.g., images or
speech). In this work, we extend an existing LLM to the speech modality via
speech discretization and continued pre-training. In particular, we are
interested in multilingual LLMs, such as TOWER, as their pre-training setting
allows us to treat discretized speech input as an additional translation
language. The resulting open-source model, SPIRE, is able to transcribe and
translate English speech input while maintaining TOWER's original performance
on translation-related tasks, showcasing that discretized speech input
integration as an additional language is feasible during LLM adaptation. We
make our code and models available to the community.
