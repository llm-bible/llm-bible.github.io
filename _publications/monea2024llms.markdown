---
layout: publication
title: 'Llms Are In-context Bandit Reinforcement Learners'
authors: Giovanni Monea, Antoine Bosselut, Kianté Brantley, Yoav Artzi
conference: "Arxiv"
year: 2024
bibkey: monea2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05362"}
tags: ['Prompting', 'In-Context Learning', 'Reinforcement Learning']
---
Large Language Models (LLMs) excel at in-context learning (ICL), a supervised
learning technique that relies on adding annotated examples to the model
context. We investigate a contextual bandit version of in-context reinforcement
learning (ICRL), where models learn in-context, online, from external reward,
instead of supervised data. We show that LLMs effectively demonstrate such
learning, and provide a detailed study of the phenomena, experimenting with
challenging classification tasks and models of sizes from 500M to 70B
parameters. This includes identifying and addressing the instability of the
process, demonstrating learning with both semantic and abstract labels, and
showing scaling trends. Our findings highlight ICRL capabilities in LLMs, while
also underscoring fundamental limitations in their implicit reasoning about
errors.
