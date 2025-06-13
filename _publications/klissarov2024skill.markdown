---
layout: publication
title: 'Maestromotif: Skill Design From Artificial Intelligence Feedback'
authors: Martin Klissarov, Mikael Henaff, Roberta Raileanu, Shagun Sodhani, Pascal Vincent, Amy Zhang, Pierre-luc Bacon, Doina Precup, Marlos C. Machado, Pierluca D'oro
conference: "Arxiv"
year: 2024
bibkey: klissarov2024skill
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08542'}
tags: ['Agentic', 'RAG', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
Describing skills in natural language has the potential to provide an
accessible way to inject human knowledge about decision-making into an AI
system. We present MaestroMotif, a method for AI-assisted skill design, which
yields high-performing and adaptable agents. MaestroMotif leverages the
capabilities of Large Language Models (LLMs) to effectively create and reuse
skills. It first uses an LLM's feedback to automatically design rewards
corresponding to each skill, starting from their natural language description.
Then, it employs an LLM's code generation abilities, together with
reinforcement learning, for training the skills and combining them to implement
complex behaviors specified in language. We evaluate MaestroMotif using a suite
of complex tasks in the NetHack Learning Environment (NLE), demonstrating that
it surpasses existing approaches in both performance and usability.
