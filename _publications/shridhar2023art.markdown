---
layout: publication
title: 'The ART Of LLM Refinement: Ask, Refine, And Trust'
authors: Shridhar Kumar, Sinha Koustuv, Cohen Andrew, Wang Tianlu, Yu Ping, Pasunuru Ram, Sachan Mrinmaya, Weston Jason, Celikyilmaz Asli
conference: "Arxiv"
year: 2023
bibkey: shridhar2023art
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07961"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
In recent years, Large Language Models (LLMs) have demonstrated remarkable
generative abilities, but can they judge the quality of their own generations?
A popular concept, referred to as self-refinement, postulates that LLMs can
detect and correct the errors in their generations when asked to do so.
However, recent empirical evidence points in the opposite direction, suggesting
that LLMs often struggle to accurately identify errors when reasoning is
involved. To address this, we propose a reasoning with refinement objective
called ART: Ask, Refine, and Trust, which asks necessary questions to decide
when an LLM should refine its output, and either affirm or withhold trust in
its refinement by ranking the refinement and the initial prediction. On two
multistep reasoning tasks of mathematical word problems (GSM8K) and question
answering (StrategyQA), ART achieves a performance gain of +5 points over
self-refinement baselines, while using a much smaller model as the decision
maker. We also demonstrate the benefit of using smaller models to make
refinement decisions as a cost-effective alternative to fine-tuning a larger
model.
