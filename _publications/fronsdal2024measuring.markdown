---
layout: publication
title: 'MISR: Measuring Instrumental Self-reasoning In Frontier Models'
authors: Kai Fronsdal, David Lindner
conference: "Arxiv"
year: 2024
bibkey: fronsdal2024measuring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03904'}
  - {name: "Code", url: 'https://github.com/kaifronsdal/Self-Reasoning-Evals'}
tags: ['Agentic', 'Has Code']
---
We propose a suite of tasks to evaluate the instrumental self-reasoning
ability of large language model (LLM) agents. Instrumental self-reasoning
ability could improve adaptability and enable self-modification, but it could
also pose significant risks, such as enabling deceptive alignment. Prior work
has only evaluated self-reasoning in non-agentic settings or in limited
domains. In this paper, we propose evaluations for instrumental self-reasoning
ability in agentic tasks in a wide range of scenarios, including
self-modification, knowledge seeking, and opaque self-reasoning. We evaluate
agents built using state-of-the-art LLMs, including commercial and open source
systems. We find that instrumental self-reasoning ability emerges only in the
most capable frontier models and that it is highly context-dependent. No model
passes the the most difficult versions of our evaluations, hence our evaluation
can be used to measure increases in instrumental self-reasoning ability in
future models. We open-source our evaluations at
https://github.com/kaifronsdal/Self-Reasoning-Evals.
