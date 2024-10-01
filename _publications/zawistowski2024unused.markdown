---
layout: publication
title: 'Unused Information In Token Probability Distribution Of Generative LLM: Improving LLM Reading Comprehension Through Calculation Of Expected Values'
authors: Zawistowski Krystian
conference: "Arxiv"
year: 2024
bibkey: zawistowski2024unused
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10267"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting']
---
'LLM text decoding is key component for perceived LLM quality. We demonstrate two experiments showing that decoding methods could be improved by manipulation of token probabilities. First, we test few LLM on SummEval summary scoring dataset, to measure reading comprehension. We compare scores from greedy decoding to expected values over the next token distribution. We scale logits by large temperature to increase the entropy of scores. This allows strong improvement of performance on SummEval (in terms of correlations to human judgement). We see improvement from 6-8&#37; to 13-28&#37; for 7B Mistral and from 20&#37;-46&#37; to 37&#37;-56&#37; for Mixtral, beating GPT 4 0314 result on two metrics. Part of the gain seems related to positional bias. Secondly, we use probability-based tree sampling algorithm, to examine all most probable generations for given prompt.'
