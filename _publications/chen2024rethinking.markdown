---
layout: publication
title: 'Rethinking Data Synthesis: A Teacher Model Training Recipe With Interpretation'
authors: Yifang Chen, David Zhu, Simon Du, Kevin Jamieson, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: chen2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20362"}
tags: ['Prompting', 'Training Techniques']
---
Recent advances in large language model (LLM) training have highlighted the
need for diverse, high-quality instruction data. Recently, many works are
exploring synthetic data generation using LLMs. However, they primarily focus
on prompt engineering with standard supervised instruction-finetuned models,
which contains a fundamental limitation: these models are optimized for general
question-answering/problem-solving rather than data generation. We propose a
paradigm shift named \textbf\{NOMAD\} by investigating how to specifically train
models for data generation, demonstrating that this task differs significantly
from training a classical LM. We identify two key factors: no-prompt-masked
training and proper training set size selection. Our method, NOMAD, shows
substantial improvements over baselines, achieving >4% gains in TriviaQA and
>2% in GSM8K with limited training data. Finally, we offer new insights by
interpreting synthetic data through the lenses of "relevance" and "novelty".
