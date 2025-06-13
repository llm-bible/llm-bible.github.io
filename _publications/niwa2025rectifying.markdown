---
layout: publication
title: 'Rectifying Belief Space Via Unlearning To Harness Llms'' Reasoning'
authors: Ayana Niwa, Masahiro Kaneko, Kentaro Inui
conference: "Arxiv"
year: 2025
bibkey: niwa2025rectifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.20620'}
tags: ['Prompting', 'Interpretability and Explainability']
---
Large language models (LLMs) can exhibit advanced reasoning yet still
generate incorrect answers. We hypothesize that such errors frequently stem
from spurious beliefs, propositions the model internally considers true but are
incorrect. To address this, we propose a method to rectify the belief space by
suppressing these spurious beliefs while simultaneously enhancing true ones,
thereby enabling more reliable inferences. Our approach first identifies the
beliefs that lead to incorrect or correct answers by prompting the model to
generate textual explanations, using our Forward-Backward Beam Search (FBBS).
We then apply unlearning to suppress the identified spurious beliefs and
enhance the true ones, effectively rectifying the model's belief space.
Empirical results on multiple QA datasets and LLMs show that our method
corrects previously misanswered questions without harming overall model
performance. Furthermore, our approach yields improved generalization on unseen
data, suggesting that rectifying a model's belief space is a promising
direction for mitigating errors and enhancing overall reliability.
