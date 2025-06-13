---
layout: publication
title: 'Are You Sure? Challenging Llms Leads To Performance Drops In The Flipflop Experiment'
authors: Philippe Laban, Lidiya Murakhovs'ka, Caiming Xiong, Chien-sheng Wu
conference: "Arxiv"
year: 2023
bibkey: laban2023are
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.08596'}
tags: ['Reinforcement Learning', 'RAG', 'Tools']
---
The interactive nature of Large Language Models (LLMs) theoretically allows
models to refine and improve their answers, yet systematic analysis of the
multi-turn behavior of LLMs remains limited. In this paper, we propose the
FlipFlop experiment: in the first round of the conversation, an LLM completes a
classification task. In a second round, the LLM is challenged with a follow-up
phrase like "Are you sure?", offering an opportunity for the model to reflect
on its initial answer, and decide whether to confirm or flip its answer. A
systematic study of ten LLMs on seven classification tasks reveals that models
flip their answers on average 46% of the time and that all models see a
deterioration of accuracy between their first and final prediction, with an
average drop of 17% (the FlipFlop effect). We conduct finetuning experiments on
an open-source LLM and find that finetuning on synthetically created data can
mitigate - reducing performance deterioration by 60% - but not resolve
sycophantic behavior entirely. The FlipFlop experiment illustrates the
universality of sycophantic behavior in LLMs and provides a robust framework to
analyze model behavior and evaluate future models.
