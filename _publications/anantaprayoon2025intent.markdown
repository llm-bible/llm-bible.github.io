---
layout: publication
title: 'Intent-aware Self-correction For Mitigating Social Biases In Large Language Models'
authors: Panatchakorn Anantaprayoon, Masahiro Kaneko, Naoaki Okazaki
conference: "Arxiv"
year: 2025
bibkey: anantaprayoon2025intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06011"}
tags: ['Bias Mitigation', 'Prompting', 'Ethics and Bias']
---
Self-Correction based on feedback improves the output quality of Large
Language Models (LLMs). Moreover, as Self-Correction functions like the slow
and conscious System-2 thinking from cognitive psychology's perspective, it can
potentially reduce LLMs' social biases. LLMs are sensitive to contextual
ambiguities and inconsistencies; therefore, explicitly communicating their
intentions during interactions when applying Self-Correction for debiasing is
crucial. In this study, we demonstrate that clarifying intentions is essential
for effectively reducing biases in LLMs through Self-Correction. We divide the
components needed for Self-Correction into three parts: instruction, response,
and feedback, and clarify intentions at each component. We incorporate an
explicit debiasing prompt to convey the intention of bias mitigation from the
instruction for response generation. In the response, we use Chain-of-Thought
(CoT) to clarify the reasoning process. In the feedback, we define evaluation
aspects necessary for debiasing and propose clear feedback through multi-aspect
critiques and scoring. Through experiments, we demonstrate that self-correcting
CoT responses obtained from a debiasing prompt based on multi-aspect feedback
can reduce biased responses more robustly and consistently than the baselines.
We also find the variation in debiasing efficacy when using models with
different bias levels or separating models for response and feedback
generation.
