---
layout: publication
title: 'A Transformer-based Approach For Smart Invocation Of Automatic Code Completion'
authors: Aral De Moor, Arie Van Deursen, Maliheh Izadi
conference: "Arxiv"
year: 2024
bibkey: demoor2024transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14753"}
tags: ['Transformer', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based language models are highly effective for code completion,
with much research dedicated to enhancing the content of these completions.
Despite their effectiveness, these models come with high operational costs and
can be intrusive, especially when they suggest too often and interrupt
developers who are concentrating on their work. Current research largely
overlooks how these models interact with developers in practice and neglects to
address when a developer should receive completion suggestions. To tackle this
issue, we developed a machine learning model that can accurately predict when
to invoke a code completion tool given the code context and available telemetry
data.
  To do so, we collect a dataset of 200k developer interactions with our
cross-IDE code completion plugin and train several invocation filtering models.
Our results indicate that our small-scale transformer model significantly
outperforms the baseline while maintaining low enough latency. We further
explore the search space for integrating additional telemetry data into a
pre-trained transformer directly and obtain promising results. To further
demonstrate our approach's practical potential, we deployed the model in an
online environment with 34 developers and provided real-world insights based on
74k actual invocations.
