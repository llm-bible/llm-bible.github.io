---
layout: publication
title: 'Safety-tuned Llamas: Lessons From Improving The Safety Of Large Language Models That Follow Instructions'
authors: Federico Bianchi, Mirac Suzgun, Giuseppe Attanasio, Paul Röttger, Dan Jurafsky, Tatsunori Hashimoto, James Zou
conference: "Arxiv"
year: 2023
bibkey: bianchi2023safety
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.07875'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Training large language models to follow instructions makes them perform
better on a wide range of tasks and generally become more helpful. However, a
perfectly helpful model will follow even the most malicious instructions and
readily generate harmful content. In this paper, we raise concerns over the
safety of models that only emphasize helpfulness, not harmlessness, in their
instruction-tuning. We show that several popular instruction-tuned models are
highly unsafe. Moreover, we show that adding just 3% safety examples (a few
hundred demonstrations) when fine-tuning a model like LLaMA can substantially
improve its safety. Our safety-tuning does not make models significantly less
capable or helpful as measured by standard benchmarks. However, we do find
exaggerated safety behaviours, where too much safety-tuning makes models refuse
perfectly safe prompts if they superficially resemble unsafe ones. As a whole,
our results illustrate trade-offs in training LLMs to be helpful and training
them to be safe.
