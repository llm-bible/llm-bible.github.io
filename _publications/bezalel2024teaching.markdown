---
layout: publication
title: 'Teaching Models To Improve On Tape'
authors: Liat Bezalel, Eyal Orgad, Amir Globerson
conference: "Arxiv"
year: 2024
bibkey: bezalel2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01483"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large Language Models (LLMs) often struggle when prompted to generate content
under specific constraints. However, in such cases it is often easy to check
whether these constraints are satisfied or violated. Recent works have shown
that LLMs can benefit from such "corrective feedback". Here we claim that this
skill of LLMs can be significantly enhanced via training. We introduce an RL
framework for teaching models to use such rewards, by simulating interaction
sessions, and rewarding the model according to its ability to satisfy the
constraints. We refer to our method as CORGI (Controlled Generation with RL for
Guided Interaction), and evaluate it on a variety of controlled generation
tasks using unlabeled training data. We find that CORGI consistently
outperforms the baseline reinforcement learning method that does not
incorporate conversational feedback. Furthermore, CORGI's interactive framework
enables meta-learning, allowing the LLM to generalize better to guided
interaction in new tasks. Our results clearly show that conversational
optimization, when combined with reinforcement learning, significantly improves
the effectiveness of LLMs in controlled generation contexts.
