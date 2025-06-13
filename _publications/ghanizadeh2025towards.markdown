---
layout: publication
title: 'Towards Data-efficient Language Models: A Child-inspired Approach To Language Learning'
authors: Mohammad Amin Ghanizadeh, Mohammad Javad Dousti
conference: "Arxiv"
year: 2025
bibkey: ghanizadeh2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04611'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
In this work, we explain our approach employed in the BabyLM Challenge, which
uses various methods of training language models (LMs) with significantly less
data compared to traditional large language models (LLMs) and are inspired by
how human children learn. While a human child is exposed to far less linguistic
input than an LLM, they still achieve remarkable language understanding and
generation abilities. To this end, we develop a model trained on a curated
dataset consisting of 10 million words, primarily sourced from child-directed
transcripts. The 2024 BabyLM Challenge initial dataset of 10M words is filtered
to 8.5M. Next, it is supplemented with a randomly selected subset of TVR
dataset consisting of 1.5M words of television dialogues. The latter dataset
ensures that similar to children, the model is also exposed to language through
media. Furthermore, we reduce the vocabulary size to 32,000 tokens, aligning it
with the limited vocabulary of children in the early stages of language
acquisition. We use curriculum learning and is able to match the baseline on
certain benchmarks while surpassing the baseline on others. Additionally,
incorporating common LLM training datasets, such as MADLAD-400, degrades
performance. These findings underscore the importance of dataset selection,
vocabulary scaling, and curriculum learning in creating more data-efficient
language models that better mimic human learning processes.
