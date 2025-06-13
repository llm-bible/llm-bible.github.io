---
layout: publication
title: 'A Comparative Study Of Dspy Teleprompter Algorithms For Aligning Large Language Models Evaluation Metrics To Human Evaluation'
authors: Bhaskarjit Sarmah, Kriti Dutta, Anna Grigoryan, Sachin Tiwari, Stefano Pasquali, Dhagash Mehta
conference: "Arxiv"
year: 2024
bibkey: sarmah2024comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15298"}
tags: ['Tools', 'Efficiency and Optimization', 'Prompting']
---
We argue that the Declarative Self-improving Python (DSPy) optimizers are a
way to align the large language model (LLM) prompts and their evaluations to
the human annotations. We present a comparative analysis of five teleprompter
algorithms, namely, Cooperative Prompt Optimization (COPRO), Multi-Stage
Instruction Prompt Optimization (MIPRO), BootstrapFewShot, BootstrapFewShot
with Optuna, and K-Nearest Neighbor Few Shot, within the DSPy framework with
respect to their ability to align with human evaluations. As a concrete
example, we focus on optimizing the prompt to align hallucination detection
(using LLM as a judge) to human annotated ground truth labels for a publicly
available benchmark dataset. Our experiments demonstrate that optimized prompts
can outperform various benchmark methods to detect hallucination, and certain
telemprompters outperform the others in at least these experiments.
