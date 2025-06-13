---
layout: publication
title: 'Catfood: Counterfactual Augmented Training For Improving Out-of-domain Performance And Calibration'
authors: Rachneet Sachdeva, Martin Tutek, Iryna Gurevych
conference: "Arxiv"
year: 2023
bibkey: sachdeva2023counterfactual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.07822'}
tags: ['Reinforcement Learning', 'Prompting', 'Interpretability and Explainability', 'Training Techniques']
---
In recent years, large language models (LLMs) have shown remarkable
capabilities at scale, particularly at generating text conditioned on a prompt.
In our work, we investigate the use of LLMs to augment training data of small
language models~(SLMs) with automatically generated counterfactual~(CF)
instances -- i.e. minimally altered inputs -- in order to improve
out-of-domain~(OOD) performance of SLMs in the extractive question
answering~(QA) setup. We show that, across various LLM generators, such data
augmentation consistently enhances OOD performance and improves model
calibration for both confidence-based and rationale-augmented calibrator
models. Furthermore, these performance improvements correlate with higher
diversity of CF instances in terms of their surface form and semantic content.
Finally, we show that CF augmented models which are easier to calibrate also
exhibit much lower entropy when assigning importance, indicating that
rationale-augmented calibrators prefer concise explanations.
