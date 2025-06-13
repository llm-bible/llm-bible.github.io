---
layout: publication
title: 'Gpt-hatecheck: Can Llms Write Better Functional Tests For Hate Speech Detection?'
authors: Yiping Jin, Leo Wanner, Alexander Shvets
conference: "Arxiv"
year: 2024
bibkey: jin2024gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15238"}
tags: ['Pre-Training', 'GPT', 'Tools', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Online hate detection suffers from biases incurred in data sampling,
annotation, and model pre-training. Therefore, measuring the averaged
performance over all examples in held-out test data is inadequate. Instead, we
must identify specific model weaknesses and be informed when it is more likely
to fail. A recent proposal in this direction is HateCheck, a suite for testing
fine-grained model functionalities on synthesized data generated using
templates of the kind "You are just a [slur] to me." However, despite enabling
more detailed diagnostic insights, the HateCheck test cases are often generic
and have simplistic sentence structures that do not match the real-world data.
To address this limitation, we propose GPT-HateCheck, a framework to generate
more diverse and realistic functional tests from scratch by instructing large
language models (LLMs). We employ an additional natural language inference
(NLI) model to verify the generations. Crowd-sourced annotation demonstrates
that the generated test cases are of high quality. Using the new functional
tests, we can uncover model weaknesses that would be overlooked using the
original HateCheck dataset.
