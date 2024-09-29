---
layout: publication
title: Fine45;grained Human Feedback Gives Better Rewards For Language Model Training
authors: Wu Zeqiu, Hu Yushi, Shi Weijia, Dziri Nouha, Suhr Alane, Ammanabrolu Prithviraj, Smith Noah A., Ostendorf Mari, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2023
bibkey: wu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01693"}
  - {name: "Code", url: "https://FineGrainedRLHF.github.io"}
tags: ['Agentic', 'Applications', 'Has Code', 'Language Modeling', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Language models (LMs) often exhibit undesirable text generation behaviors including generating false toxic or irrelevant outputs. Reinforcement learning from human feedback (RLHF) 45; where human preference judgments on LM outputs are transformed into a learning signal 45; has recently shown promise in addressing these issues. However such holistic feedback conveys limited information on long text outputs; it does not indicate which aspects of the outputs influenced user preference; e.g. which parts contain what type(s) of errors. In this paper we use fine45;grained human feedback (e.g. which sentence is false which sub45;sentence is irrelevant) as an explicit training signal. We introduce Fine45;Grained RLHF a framework that enables training and learning from reward functions that are fine45;grained in two respects (1) density providing a reward after every segment (e.g. a sentence) is generated; and (2) incorporating multiple reward models associated with different feedback types (e.g. factual incorrectness irrelevance and information incompleteness). We conduct experiments on detoxification and long45;form question answering to illustrate how learning with such reward functions leads to improved performance supported by both automatic and human evaluation. Additionally we show that LM behaviors can be customized using different combinations of fine45;grained reward models. We release all data collected human feedback and codes at https://FineGrainedRLHF.github.io.
