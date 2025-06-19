---
layout: publication
title: Reasoning About Actions And State Changes By Injecting Commonsense Knowledge
authors: Niket Tandon et al.
conference: Arxiv
year: 2018
citations: 15
bibkey: tandon2018reasoning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10012'}]
tags: [Ethics and Bias, Reinforcement Learning]
---
Comprehending procedural text, e.g., a paragraph describing photosynthesis,
requires modeling actions and the state changes they produce, so that questions
about entities at different timepoints can be answered. Although several recent
systems have shown impressive progress in this task, their predictions can be
globally inconsistent or highly improbable. In this paper, we show how the
predicted effects of actions in the context of a paragraph can be improved in
two ways: (1) by incorporating global, commonsense constraints (e.g., a
non-existent entity cannot be destroyed), and (2) by biasing reading with
preferences from large-scale corpora (e.g., trees rarely move). Unlike earlier
methods, we treat the problem as a neural structured prediction task, allowing
hard and soft constraints to steer the model away from unlikely predictions. We
show that the new model significantly outperforms earlier systems on a
benchmark dataset for procedural text comprehension (+8% relative gain), and
that it also avoids some of the nonsensical predictions that earlier systems
make.