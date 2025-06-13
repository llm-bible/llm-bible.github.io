---
layout: publication
title: 'You''ve Changed: Detecting Modification Of Black-box Large Language Models'
authors: Alden Dima, James Foulds, Shimei Pan, Philip Feldman
conference: "Arxiv"
year: 2025
bibkey: dima2025detecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12335'}
tags: ['Prompting', 'Security', 'Tools']
---
Large Language Models (LLMs) are often provided as a service via an API,
making it challenging for developers to detect changes in their behavior. We
present an approach to monitor LLMs for changes by comparing the distributions
of linguistic and psycholinguistic features of generated text. Our method uses
a statistical test to determine whether the distributions of features from two
samples of text are equivalent, allowing developers to identify when an LLM has
changed. We demonstrate the effectiveness of our approach using five OpenAI
completion models and Meta's Llama 3 70B chat model. Our results show that
simple text features coupled with a statistical test can distinguish between
language models. We also explore the use of our approach to detect prompt
injection attacks. Our work enables frequent LLM change monitoring and avoids
computationally expensive benchmark evaluations.
