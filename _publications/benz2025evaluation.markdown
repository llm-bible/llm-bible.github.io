---
layout: publication
title: 'Evaluation Of Large Language Models Via Coupled Token Generation'
authors: Nina Corvelo Benz, Stratis Tsirtsis, Eleni Straitouri, Ivi Chatzi, Ander Artola Velasco, Suhas Thejaswi, Manuel Gomez-rodriguez
conference: "Arxiv"
year: 2025
bibkey: benz2025evaluation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01754'}
tags: ['Prompting', 'GPT', 'Tools', 'Pretraining Methods']
---
State of the art large language models rely on randomization to respond to a
prompt. As an immediate consequence, a model may respond differently to the
same prompt if asked multiple times. In this work, we argue that the evaluation
and ranking of large language models should control for the randomization
underpinning their functioning. Our starting point is the development of a
causal model for coupled autoregressive generation, which allows different
large language models to sample responses with the same source of randomness.
Building upon our causal model, we first show that, on evaluations based on
benchmark datasets, coupled autoregressive generation leads to the same
conclusions as vanilla autoregressive generation but using provably fewer
samples. However, we further show that, on evaluations based on (human)
pairwise comparisons, coupled and vanilla autoregressive generation can
surprisingly lead to different rankings when comparing more than two models,
even with an infinite amount of samples. This suggests that the apparent
advantage of a model over others in existing evaluation protocols may not be
genuine but rather confounded by the randomness inherent to the generation
process. To illustrate and complement our theoretical results, we conduct
experiments with several large language models from the Llama family. We find
that, across multiple knowledge areas from the popular MMLU benchmark dataset,
coupled autoregressive generation requires up to 40% fewer samples to reach the
same conclusions as vanilla autoregressive generation. Further, using data from
the LMSYS Chatbot Arena platform, we find that the win-rates derived from
pairwise comparisons by a strong large language model to prompts differ under
coupled and vanilla autoregressive generation.
