---
layout: publication
title: 'Tangoflux: Super Fast And Faithful Text To Audio Generation With Flow Matching And Clap-ranked Preference Optimization'
authors: Chia-yu Hung, Navonil Majumder, Zhifeng Kong, Ambuj Mehrish, Amir Ali Bagherzadeh, Chuan Li, Rafael Valle, Bryan Catanzaro, Soujanya Poria
conference: "Arxiv"
year: 2024
bibkey: hung2024super
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.21037'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Tools']
---
We introduce TangoFlux, an efficient Text-to-Audio (TTA) generative model
with 515M parameters, capable of generating up to 30 seconds of 44.1kHz audio
in just 3.7 seconds on a single A40 GPU. A key challenge in aligning TTA models
lies in the difficulty of creating preference pairs, as TTA lacks structured
mechanisms like verifiable rewards or gold-standard answers available for Large
Language Models (LLMs). To address this, we propose CLAP-Ranked Preference
Optimization (CRPO), a novel framework that iteratively generates and optimizes
preference data to enhance TTA alignment. We demonstrate that the audio
preference dataset generated using CRPO outperforms existing alternatives. With
this framework, TangoFlux achieves state-of-the-art performance across both
objective and subjective benchmarks. We open source all code and models to
support further research in TTA generation.
