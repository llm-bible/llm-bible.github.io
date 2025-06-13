---
layout: publication
title: 'General Intelligence Requires Reward-based Pretraining'
authors: Seungwook Han, Jyothish Pari, Samuel J. Gershman, Pulkit Agrawal
conference: "Arxiv"
year: 2025
bibkey: han2025general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19402"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated impressive real-world utility, exemplifying artificial useful intelligence (AUI). However, their ability to reason adaptively and robustly -- the hallmarks of artificial general intelligence (AGI) -- remains fragile. While LLMs seemingly succeed in commonsense reasoning, programming, and mathematics, they struggle to generalize algorithmic understanding across novel contexts. Our experiments with algorithmic tasks in esoteric programming languages reveal that LLM's reasoning overfits to the training data and is limited in its transferability. We hypothesize that the core issue underlying such limited transferability is the coupling of reasoning and knowledge in LLMs.
  To transition from AUI to AGI, we propose disentangling knowledge and reasoning through three key directions: (1) pretaining to reason using RL from scratch as an alternative to the widely used next-token prediction pretraining, (2) using a curriculum of synthetic tasks to ease the learning of a reasoning prior for RL that can then be transferred to natural language tasks, and (3) learning more generalizable reasoning functions using a small context window to reduce exploiting spurious correlations between tokens. Such a reasoning system coupled with a trained retrieval system and a large external memory bank as a knowledge store can overcome several limitations of existing architectures at learning to reason in novel scenarios.
