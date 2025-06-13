---
layout: publication
title: 'Lightweight Reranking For Language Model Generations'
authors: Siddhartha Jain, Xiaofei Ma, Anoop Deoras, Bing Xiang
conference: "Arxiv"
year: 2023
bibkey: jain2023lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.06857"}
tags: ['Training Techniques', 'Applications', 'Tools']
---
Large Language Models (LLMs) can exhibit considerable variation in the
quality of their sampled outputs. Reranking and selecting the best generation
from the sampled set is a popular way of obtaining strong gains in generation
quality. In this paper, we present a novel approach for reranking LLM
generations. Unlike other techniques that might involve additional inferences
or training a specialized reranker, our approach relies on easy to compute
pairwise statistics between the generations that have minimal compute overhead.
We show that our approach can be formalized as an extension of self-consistency
and analyze its performance in that framework, theoretically as well as via
simulations. We show strong improvements for selecting the best k generations
for code generation tasks as well as robust improvements for the best
generation for the tasks of autoformalization, summarization, and translation.
While our approach only assumes black-box access to LLMs, we show that
additional access to token probabilities can improve performance even further.
