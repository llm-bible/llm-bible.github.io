---
layout: publication
title: 'Summarization Metrics For Spanish And Basque: Do Automatic Scores And Llm-judges Correlate With Humans?'
authors: Jeremy Barnes, Naiara Perez, Alba Bonet-jover, Begoña Altuna
conference: "Arxiv"
year: 2025
bibkey: barnes2025summarization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17039"}
tags: ['Prompting', 'Applications', 'Reinforcement Learning']
---
Studies on evaluation metrics and LLM-as-a-Judge models for automatic text
summarization have largely been focused on English, limiting our understanding
of their effectiveness in other languages. Through our new dataset BASSE
(BAsque and Spanish Summarization Evaluation), we address this situation by
collecting human judgments on 2,040 abstractive summaries in Basque and
Spanish, generated either manually or by five LLMs with four different prompts.
For each summary, annotators evaluated five criteria on a 5-point Likert scale:
coherence, consistency, fluency, relevance, and 5W1H. We use these data to
reevaluate traditional automatic metrics used for evaluating summaries, as well
as several LLM-as-a-Judge models that show strong performance on this task in
English. Our results show that currently proprietary judge LLMs have the
highest correlation with human judgments, followed by criteria-specific
automatic metrics, while open-sourced judge LLMs perform poorly. We release
BASSE and our code publicly, along with the first large-scale Basque
summarization dataset containing 22,525 news articles with their subheads.
