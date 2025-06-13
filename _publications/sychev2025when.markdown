---
layout: publication
title: 'When An LLM Is Apprehensive About Its Answers -- And When Its Uncertainty Is Justified'
authors: Petr Sychev, Andrey Goncharov, Daniil Vyazhev, Edvard Khalafyan, Alexey Zaytsev
conference: "Arxiv"
year: 2025
bibkey: sychev2025when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01688"}
tags: ['Ethics and Bias', 'Tools', 'Reinforcement Learning']
---
Uncertainty estimation is crucial for evaluating Large Language Models
(LLMs), particularly in high-stakes domains where incorrect answers result in
significant consequences. Numerous approaches consider this problem, while
focusing on a specific type of uncertainty, ignoring others. We investigate
what estimates, specifically token-wise entropy and model-as-judge (MASJ),
would work for multiple-choice question-answering tasks for different question
topics. Our experiments consider three LLMs: Phi-4, Mistral, and Qwen of
different sizes from 1.5B to 72B and \\(14\\) topics. While MASJ performs similarly
to a random error predictor, the response entropy predicts model error in
knowledge-dependent domains and serves as an effective indicator of question
difficulty: for biology ROC AUC is \\(0.73\\). This correlation vanishes for the
reasoning-dependent domain: for math questions ROC-AUC is \\(0.55\\). More
principally, we found out that the entropy measure required a reasoning amount.
Thus, data-uncertainty related entropy should be integrated within uncertainty
estimates frameworks, while MASJ requires refinement. Moreover, existing
MMLU-Pro samples are biased, and should balance required amount of reasoning
for different subdomains to provide a more fair assessment of LLMs performance.
