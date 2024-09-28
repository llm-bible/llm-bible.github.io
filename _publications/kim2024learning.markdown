---
layout: publication
title: Learning to Correct for QA Reasoning with Black-box LLMs
authors: Kim Jaehyung, Kim Dongyoung, Yang Yiming
conference: "Arxiv"
year: 2024
bibkey: kim2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18695"}
tags: ['ARXIV', 'Efficiency And Optimization', 'Fine Tuning', 'LLM']
---
An open challenge in recent machine learning is about how to improve the reasoning capability of large language models (LLMs) in a black-box setting i.e. without access to detailed information such as output token probabilities. Existing approaches either rely on accessibility (which is often unrealistic) or involve significantly increased train- and inference-time costs. This paper addresses those limitations or shortcomings by proposing a novel approach namely CoBB (Correct for improving QA reasoning of Black-Box LLMs). It uses a trained adaptation model to perform a seq2seq mapping from the often-imperfect reasonings of the original black-box LLM to the correct or improved reasonings. Specifically the adaptation model is initialized with a relatively small open-source LLM and adapted over a collection of sub-sampled training pairs. To select the representative pairs of correct and incorrect reasonings we formulated the dataset construction as an optimization problem that minimizes the statistical divergence between the sampled subset and the entire collection and solved it via a genetic algorithm. We then train the adaptation model over the sampled pairs by contrasting the likelihoods of correct and incorrect reasonings. Our experimental results demonstrate that CoBB significantly improves reasoning accuracy across various QA benchmarks compared to the best-performing adaptation baselines.
