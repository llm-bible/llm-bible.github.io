---
layout: publication
title: Controllable Neural Story Plot Generation Via Reward Shaping
authors: Pradyumna Tambwekar et al.
conference: In International Joint Conference on Artificial Intelligence (IJCAI) Macau
  China Jul. 2019 pp. 5982-5988
year: 2018
citations: 28
bibkey: tambwekar2018controllable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.10736'}]
tags: [Reinforcement Learning, Tools]
---
Language-modeling--based approaches to story plot generation attempt to
construct a plot by sampling from a language model (LM) to predict the next
character, word, or sentence to add to the story. LM techniques lack the
ability to receive guidance from the user to achieve a specific goal, resulting
in stories that don't have a clear sense of progression and lack coherence. We
present a reward-shaping technique that analyzes a story corpus and produces
intermediate rewards that are backpropagated into a pre-trained LM in order to
guide the model towards a given goal. Automated evaluations show our technique
can create a model that generates story plots which consistently achieve a
specified goal. Human-subject studies show that the generated stories have more
plausible event ordering than baseline plot generation techniques.