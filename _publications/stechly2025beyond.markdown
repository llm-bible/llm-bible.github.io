---
layout: publication
title: 'Beyond Semantics: The Unreasonable Effectiveness Of Reasonless Intermediate Tokens'
authors: Kaya Stechly, Karthik Valmeekam, Atharva Gundawar, Vardhan Palod, Subbarao Kambhampati
conference: "Arxiv"
year: 2025
bibkey: stechly2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13775'}
tags: ['Training Techniques', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Recent impressive results from large reasoning models have been interpreted as a triumph of Chain of Thought (CoT), and especially of the process of training on CoTs sampled from base LLMs in order to help find new reasoning patterns. In this paper, we critically examine that interpretation by investigating how the semantics of intermediate tokens-often anthropomorphized as "thoughts" or reasoning traces and which are claimed to display behaviors like backtracking, self-verification etc.-actually influence model performance. We train transformer models on formally verifiable reasoning traces and solutions, constraining both intermediate steps and final outputs to align with those of a formal solver (in our case, A* search). By constructing a formal interpreter of the semantics of our problems and intended algorithm, we systematically evaluate not only solution accuracy but also the correctness of intermediate traces, thus allowing us to evaluate whether the latter causally influences the former. We notice that, despite significant improvements on the solution-only baseline, models trained on entirely correct traces still produce invalid reasoning traces when arriving at correct solutions. To further show that trace accuracy is only loosely connected to solution accuracy, we then train models on noisy, corrupted traces which have no relation to the specific problem each is paired with, and find that not only does performance remain largely consistent with models trained on correct data, but in some cases can improve upon it and generalize more robustly on out-of-distribution tasks. These results challenge the assumption that intermediate tokens or "Chains of Thought" induce predictable reasoning behaviors and caution against anthropomorphizing such outputs or over-interpreting them (despite their mostly correct forms) as evidence of human-like or algorithmic behaviors in language models.
