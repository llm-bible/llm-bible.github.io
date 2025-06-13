---
layout: publication
title: 'The Challenge Of Using Llms To Simulate Human Behavior: A Causal Inference Perspective'
authors: George Gui, Olivier Toubia
conference: "Arxiv"
year: 2023
bibkey: gui2023challenge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15524"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have shown impressive potential to simulate
human behavior. We identify a fundamental challenge in using them to simulate
experiments: when LLM-simulated subjects are blind to the experimental design
(as is standard practice with human subjects), variations in treatment
systematically affect unspecified variables that should remain constant,
violating the unconfoundedness assumption. Using demand estimation as a context
and an actual experiment as a benchmark, we show this can lead to implausible
results. While confounding may in principle be addressed by controlling for
covariates, this can compromise ecological validity in the context of LLM
simulations: controlled covariates become artificially salient in the simulated
decision process, which introduces focalism. This trade-off between
unconfoundedness and ecological validity is usually absent in traditional
experimental design and represents a unique challenge in LLM simulations. We
formalize this challenge theoretically, showing it stems from ambiguous
prompting strategies, and hence cannot be fully addressed by improving training
data or by fine-tuning. Alternative approaches that unblind the experimental
design to the LLM show promise. Our findings suggest that effectively
leveraging LLMs for experimental simulations requires fundamentally rethinking
established experimental design practices rather than simply adapting protocols
developed for human subjects.
