---
layout: publication
title: 'Test-time Fairness And Robustness In Large Language Models'
authors: Leonardo Cotta, Chris J. Maddison
conference: "Arxiv"
year: 2024
bibkey: cotta2024test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07685"}
tags: ['Security', 'Training Techniques', 'Fairness', 'Reinforcement Learning', 'RAG', 'Bias Mitigation', 'Ethics and Bias', 'Prompting', 'Pre-Training']
---
Frontier Large Language Models (LLMs) can be socially discriminatory or
sensitive to spurious features of their inputs. Because only well-resourced
corporations can train frontier LLMs, we need robust test-time strategies to
control such biases. Existing solutions, which instruct the LLM to be fair or
robust, rely on the model's implicit understanding of bias. Causality provides
a rich formalism through which we can be explicit about our debiasing
requirements. Yet, as we show, a naive application of the standard causal
debiasing strategy, counterfactual data augmentation, fails under standard
assumptions to debias predictions at an individual level at test time. To
address this, we develop a stratified notion of debiasing called stratified
invariance, which can capture a range of debiasing requirements from population
level to individual level through an additional measurement that stratifies the
predictions. We present a complete observational test for stratified
invariance. Finally, we introduce a data augmentation strategy that guarantees
stratified invariance at test time under suitable assumptions, together with a
prompting strategy that encourages stratified invariance in LLMs. We show that
our prompting strategy, unlike implicit instructions, consistently reduces the
bias of frontier LLMs across a suite of synthetic and real-world benchmarks
without requiring additional data, finetuning or pre-training.
