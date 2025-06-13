---
layout: publication
title: 'Hero At Averitec: The Herd Of Open Large Language Models For Verifying Real-world Claims'
authors: Yejun Yoon, Jaeyoon Jung, Seunghyun Yoon, Kunwoo Park
conference: "Arxiv"
year: 2024
bibkey: yoon2024hero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12377"}
  - {name: "Code", url: "https://github.com/ssu-humane/HerO"}
tags: ['Prompting', 'Has Code', 'Reinforcement Learning']
---
To tackle the AVeriTeC shared task hosted by the FEVER-24, we introduce a
system that only employs publicly available large language models (LLMs) for
each step of automated fact-checking, dubbed the Herd of Open LLMs for
verifying real-world claims (HerO). For evidence retrieval, a language model is
used to enhance a query by generating hypothetical fact-checking documents. We
prompt pretrained and fine-tuned LLMs for question generation and veracity
prediction by crafting prompts with retrieved in-context samples. HerO achieved
2nd place on the leaderboard with the AVeriTeC score of 0.57, suggesting the
potential of open LLMs for verifying real-world claims. For future research, we
make our code publicly available at https://github.com/ssu-humane/HerO.
