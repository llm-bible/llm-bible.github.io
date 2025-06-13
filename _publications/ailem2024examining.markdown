---
layout: publication
title: 'Examining The Robustness Of LLM Evaluation To The Distributional Assumptions Of Benchmarks'
authors: Melissa Ailem, Katerina Marazopoulou, Charlotte Siska, James Bono
conference: "Arxiv"
year: 2024
bibkey: ailem2024examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16966"}
tags: ['RAG', 'Security', 'Prompting', 'Reinforcement Learning']
---
Benchmarks have emerged as the central approach for evaluating Large Language
Models (LLMs). The research community often relies on a model's average
performance across the test prompts of a benchmark to evaluate the model's
performance. This is consistent with the assumption that the test prompts
within a benchmark represent a random sample from a real-world distribution of
interest. We note that this is generally not the case; instead, we hold that
the distribution of interest varies according to the specific use case. We find
that (1) the correlation in model performance across test prompts is
non-random, (2) accounting for correlations across test prompts can change
model rankings on major benchmarks, (3) explanatory factors for these
correlations include semantic similarity and common LLM failure points.
