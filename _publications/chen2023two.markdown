---
layout: publication
title: Two Failures of Self-Consistency in the Multi-Step Reasoning of LLMs
authors: Chen Angelica, Phang Jason, Parrish Alicia, Padmakumar Vishakh, Zhao Chen, Bowman Samuel R., Cho Kyunghyun
conference: "Transactions on Machine Learning Research"
year: 2023
bibkey: chen2023two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14279"}
tags: ['Few Shot', 'GPT', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved widespread success on a variety of in-context few-shot tasks but this success is typically evaluated via correctness rather than consistency. We argue that self-consistency is an important criteria for valid multi-step reasoning in tasks where the solution is composed of the answers to multiple sub-steps. We propose two types of self-consistency that are particularly important for multi-step reasoning -- hypothetical consistency (a models ability to predict what its output would be in a hypothetical other context) and compositional consistency (consistency of a models final outputs when intermediate sub-steps are replaced with the models outputs for those steps). We demonstrate that multiple variants of the GPT-3/-4 models exhibit poor consistency rates across both types of consistency on a variety of tasks.
