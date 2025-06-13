---
layout: publication
title: 'Reinforcing Compositional Retrieval: Retrieving Step-by-step For Composing Informative Contexts'
authors: Quanyu Long, Jianda Chen, Zhengyuan Liu, Nancy F. Chen, Wenya Wang, Sinno Jialin Pan
conference: "Arxiv"
year: 2025
bibkey: long2025reinforcing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11420'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
numerous tasks, yet they often rely on external context to handle complex
tasks. While retrieval-augmented frameworks traditionally focus on selecting
top-ranked documents in a single pass, many real-world scenarios demand
compositional retrieval, where multiple sources must be combined in a
coordinated manner. In this work, we propose a tri-encoder sequential retriever
that models this process as a Markov Decision Process (MDP), decomposing the
probability of retrieving a set of elements into a sequence of conditional
probabilities and allowing each retrieval step to be conditioned on previously
selected examples. We train the retriever in two stages: first, we efficiently
construct supervised sequential data for initial policy training; we then
refine the policy to align with the LLM's preferences using a reward grounded
in the structural correspondence of generated programs. Experimental results
show that our method consistently and significantly outperforms baselines,
underscoring the importance of explicitly modeling inter-example dependencies.
These findings highlight the potential of compositional retrieval for tasks
requiring multiple pieces of evidence or examples.
