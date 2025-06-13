---
layout: publication
title: 'Noiser: Bounded Input Perturbations For Attributing Large Language Models'
authors: Mohammad Reza Ghasemi Madani, Aryo Pradipta Gema, Gabriele Sarti, Yu Zhao, Pasquale Minervini, Andrea Passerini
conference: "Arxiv"
year: 2025
bibkey: madani2025bounded
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02911'}
tags: ['Attention Mechanism', 'Security', 'Model Architecture']
---
Feature attribution (FA) methods are common post-hoc approaches that explain
how Large Language Models (LLMs) make predictions. Accordingly, generating
faithful attributions that reflect the actual inner behavior of the model is
crucial. In this paper, we introduce Noiser, a perturbation-based FA method
that imposes bounded noise on each input embedding and measures the robustness
of the model against partially noised input to obtain the input attributions.
Additionally, we propose an answerability metric that employs an instructed
judge model to assess the extent to which highly scored tokens suffice to
recover the predicted output. Through a comprehensive evaluation across six
LLMs and three tasks, we demonstrate that Noiser consistently outperforms
existing gradient-based, attention-based, and perturbation-based FA methods in
terms of both faithfulness and answerability, making it a robust and effective
approach for explaining language model predictions.
