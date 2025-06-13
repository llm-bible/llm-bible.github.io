---
layout: publication
title: 'Using Large Language Models For Zero-shot Natural Language Generation From Knowledge Graphs'
authors: Agnes Axelsson, Gabriel Skantze
conference: "Arxiv"
year: 2023
bibkey: axelsson2023using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07312"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Applications']
---
In any system that uses structured knowledge graph (KG) data as its
underlying knowledge representation, KG-to-text generation is a useful tool for
turning parts of the graph data into text that can be understood by humans.
Recent work has shown that models that make use of pretraining on large amounts
of text data can perform well on the KG-to-text task even with relatively small
sets of training data on the specific graph-to-text task. In this paper, we
build on this concept by using large language models to perform zero-shot
generation based on nothing but the model's understanding of the triple
structure from what it can read. We show that ChatGPT achieves near
state-of-the-art performance on some measures of the WebNLG 2020 challenge, but
falls behind on others. Additionally, we compare factual, counter-factual and
fictional statements, and show that there is a significant connection between
what the LLM already knows about the data it is parsing and the quality of the
output text.
