---
layout: publication
title: 'Qtok: A Comprehensive Framework For Evaluating Multilingual Tokenizer Quality In Large Language Models'
authors: Iaroslav Chelombitko, Egor Safronov, Aleksey Komissarov
conference: "Arxiv"
year: 2024
bibkey: chelombitko2024comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.12989'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Tokenization']
---
In the development of Large Language Models (LLMs), considerable attention
has been given to the quality of training datasets. However, the role of
tokenizers in the LLM training pipeline, particularly for multilingual models,
has received less focus. The quality of tokenization can significantly impact a
model's ability to handle diverse languages effectively. We introduce Qtok, a
tool designed to assess tokenizer quality with a specific emphasis on their
performance in multilingual contexts.
  Our research proposes a set of metrics for evaluating tokenizer quality,
including measures of language coverage, token completeness, and distribution
across languages and linguistic categories. Qtok applies these metrics to
evaluate 13 distinct tokenizers from 58 publicly available models, analyzing
their output across different linguistic contexts. Our analysis revealed
significant variations in token distribution across languages and categories,
highlighting potential biases and areas for improvement in current tokenization
strategies.
  This research contributes to the field of tokenizer evaluation within
multilingual LLM development by providing a systematic approach to assessing
tokenizer quality. Our findings highlight the critical role of tokenization in
multilingual LLM capability. The Qtok tool and our analysis methodology offer
practical means for researchers to evaluate and improve tokenization strategies
for multilingual applications. We offer a method to compare tokenizer quality
across these metrics, which may be useful when selecting or adjusting
tokenizers for specific multilingual LLM applications.
