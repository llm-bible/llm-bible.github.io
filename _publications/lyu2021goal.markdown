---
layout: publication
title: 'Goal-oriented Script Construction'
authors: Qing Lyu, Li Zhang, Chris Callison-burch
conference: "Arxiv"
year: 2021
bibkey: lyu2021goal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.13189"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications']
---
The knowledge of scripts, common chains of events in stereotypical scenarios,
is a valuable asset for task-oriented natural language understanding systems.
We propose the Goal-Oriented Script Construction task, where a model produces a
sequence of steps to accomplish a given goal. We pilot our task on the first
multilingual script learning dataset supporting 18 languages collected from
wikiHow, a website containing half a million how-to articles. For baselines, we
consider both a generation-based approach using a language model and a
retrieval-based approach by first retrieving the relevant steps from a large
candidate pool and then ordering them. We show that our task is practical,
feasible but challenging for state-of-the-art Transformer models, and that our
methods can be readily deployed for various other datasets and domains with
decent zero-shot performance.
