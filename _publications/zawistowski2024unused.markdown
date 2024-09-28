---
layout: publication
title: Unused information in token probability distribution of generative LLM improving LLM reading comprehension through calculation of expected values
authors: Zawistowski Krystian
conference: "Arxiv"
year: 2024
bibkey: zawistowski2024unused
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10267"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'LLM']
---
LLM text decoding is key component for perceived LLM quality. We demonstrate two experiments showing that decoding methods could be improved by manipulation of token probabilities. First we test few LLM on SummEval summary scoring dataset to measure reading comprehension. We compare scores from greedy decoding to expected values over the next token distribution. We scale logits by large temperature to increase the entropy of scores. This allows strong improvement of performance on SummEval (in terms of correlations to human judgement). We see improvement from 6-8 to 13-28 for 7B Mistral and from 20-46 to 37-56 for Mixtral beating GPT 4 0314 result on two metrics. Part of the gain seems related to positional bias. Secondly we use probability-based tree sampling algorithm to examine all most probable generations for given prompt.
