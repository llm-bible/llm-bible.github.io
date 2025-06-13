---
layout: publication
title: 'Towards The Pedagogical Steering Of Large Language Models For Tutoring: A Case Study With Modeling Productive Failure'
authors: Romain Puech, Jakub Macina, Julia Chatain, Mrinmaya Sachan, Manu Kapur
conference: "Arxiv"
year: 2024
bibkey: puech2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03781"}
tags: ['Prompting', 'Reinforcement Learning']
---
One-to-one tutoring is one of the most efficient methods of teaching. With
the growing popularity of Large Language Models (LLMs), there have been efforts
to create LLM based conversational tutors which can expand the benefits of one
to one tutoring to everyone. However, current LLMs are trained primarily to be
helpful assistants and lack crucial pedagogical skills. For example, they often
quickly reveal the solution to the student and fail to plan for a richer multi
turn pedagogical interaction. To use LLMs in pedagogical settings, they need to
be steered to use effective teaching strategies: a problem we introduce as
Pedagogical Steering. We develop StratL, an algorithm to optimize LLM prompts
and steer it to follow a predefined multi-turn tutoring plan represented as a
transition graph. As a case study, we create a prototype tutor for high school
math following Productive Failure (PF), an advanced and effective learning
design. To validate our approach in a real-world setting, we run a field study
with 17 high school students in Singapore and show that StratL succeeds in
steering the LLM to follow the PF tutoring strategy. Finally, we highlight
challenges in Pedagogical Steering of LLMs and offer opportunities for further
improvements by publishing a dataset of PF problems and our code.
