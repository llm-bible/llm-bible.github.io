---
layout: publication
title: 'Derailing Non-answers Via Logit Suppression At Output Subspace Boundaries In Rlhf-aligned Language Models'
authors: Harvey Dam, Jonas Knochelmann, Vinu Joseph, Ganesh Gopalakrishnan
conference: "Arxiv"
year: 2025
bibkey: dam2025derailing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23848'}
tags: ['Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
We introduce a method to reduce refusal rates of large language models (LLMs) on sensitive content without modifying model weights or prompts. Motivated by the observation that refusals in certain models were often preceded by the specific token sequence of a token marking the beginning of the chain-of-thought (CoT) block (<think>) followed by a double newline token (\n\n), we investigate the impact of two simple formatting adjustments during generation: suppressing \n\n after <think> and suppressing the end-of-sequence token after the end of the CoT block (</think>). Our method requires no datasets, parameter changes, or training, relying solely on modifying token probabilities during generation. In our experiments with official DeepSeek-R1 distillations, these interventions increased the proportion of substantive answers to sensitive prompts without affecting performance on standard benchmarks. Our findings suggest that refusal behaviors can be circumvented by blocking refusal subspaces at specific points in the generation process.
