---
layout: publication
title: 'LAMP: A Language Model On The Map'
authors: Pasquale Balsebre, Weiming Huang, Gao Cong
conference: "Arxiv"
year: 2024
bibkey: balsebre2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09059"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are poised to play an increasingly important
role in our lives, providing assistance across a wide array of tasks. In the
geospatial domain, LLMs have demonstrated the ability to answer generic
questions, such as identifying a country's capital; nonetheless, their utility
is hindered when it comes to answering fine-grained questions about specific
places, such as grocery stores or restaurants, which constitute essential
aspects of people's everyday lives. This is mainly because the places in our
cities haven't been systematically fed into LLMs, so as to understand and
memorize them. This study introduces a novel framework for fine-tuning a
pre-trained model on city-specific data, to enable it to provide accurate
recommendations, while minimizing hallucinations. We share our model, LAMP, and
the data used to train it. We conduct experiments to analyze its ability to
correctly retrieving spatial objects, and compare it to well-known open- and
closed- source language models, such as GPT-4. Finally, we explore its emerging
capabilities through a case study on day planning.
