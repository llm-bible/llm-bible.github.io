---
layout: publication
title: 'From Language To Programs: Bridging Reinforcement Learning And Maximum Marginal
  Likelihood'
authors: Kelvin Guu, Panupong Pasupat, Evan Zheran Liu, Percy Liang
conference: Arxiv
year: 2017
citations: 25
bibkey: guu2017from
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.07926'}]
tags: [Fine-Tuning, Reinforcement Learning, Agentic]
---
Our goal is to learn a semantic parser that maps natural language utterances
into executable programs when only indirect supervision is available: examples
are labeled with the correct execution result, but not the program itself.
Consequently, we must search the space of programs for those that output the
correct result, while not being misled by spurious programs: incorrect programs
that coincidentally output the correct result. We connect two common learning
paradigms, reinforcement learning (RL) and maximum marginal likelihood (MML),
and then present a new learning algorithm that combines the strengths of both.
The new algorithm guards against spurious programs by combining the systematic
search traditionally employed in MML with the randomized exploration of RL, and
by updating parameters such that probability is spread more evenly across
consistent programs. We apply our learning algorithm to a new neural semantic
parser and show significant gains over existing state-of-the-art results on a
recent context-dependent semantic parsing task.