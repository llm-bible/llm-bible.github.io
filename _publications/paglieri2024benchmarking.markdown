---
layout: publication
title: 'BALROG: Benchmarking Agentic LLM And VLM Reasoning On Games'
authors: Davide Paglieri, Bartłomiej Cupiał, Samuel Coward, Ulyana Piterbarg, Maciej Wolczyk, Akbir Khan, Eduardo Pignatelli, Łukasz Kuciński, Lerrel Pinto, Rob Fergus, Jakob Nicolaus Foerster, Jack Parker-holder, Tim Rocktäschel
conference: "Arxiv"
year: 2024
bibkey: paglieri2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13543"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning']
---
Large Language Models (LLMs) and Vision Language Models (VLMs) possess
extensive knowledge and exhibit promising reasoning abilities, however, they
still struggle to perform well in complex, dynamic environments. Real-world
tasks require handling intricate interactions, advanced spatial reasoning,
long-term planning, and continuous exploration of new strategies-areas in which
we lack effective methodologies for comprehensively evaluating these
capabilities. To address this gap, we introduce BALROG, a novel benchmark
designed to assess the agentic capabilities of LLMs and VLMs through a diverse
set of challenging games. Our benchmark incorporates a range of existing
reinforcement learning environments with varying levels of difficulty,
including tasks that are solvable by non-expert humans in seconds to extremely
challenging ones that may take years to master (e.g., the NetHack Learning
Environment). We devise fine-grained metrics to measure performance and conduct
an extensive evaluation of several popular open-source and closed-source LLMs
and VLMs. Our findings indicate that while current models achieve partial
success in the easier games, they struggle significantly with more challenging
tasks. Notably, we observe severe deficiencies in vision-based decision-making,
as several models perform worse when visual representations of the environments
are provided. We release BALROG as an open and user-friendly benchmark to
facilitate future research and development in the agentic community. Code and
Leaderboard at balrogai.com.
