---
layout: publication
title: 'Generating Computational Cognitive Models Using Large Language Models'
authors: Milena Rmus, Akshay K. Jagadish, Marvin Mathony, Tobias Ludwig, Eric Schulz
conference: "Arxiv"
year: 2025
bibkey: rmus2025generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00879'}
tags: ['RAG', 'Interpretability', 'Prompting']
---
Computational cognitive models, which formalize theories of cognition, enable researchers to quantify cognitive processes and arbitrate between competing theories by fitting models to behavioral data. Traditionally, these models are handcrafted, which requires significant domain knowledge, coding expertise, and time investment. However, recent advances in machine learning offer solutions to these challenges. In particular, Large Language Models (LLMs) have demonstrated remarkable capabilities for in-context pattern recognition, leveraging knowledge from diverse domains to solve complex problems, and generating executable code that can be used to facilitate the generation of cognitive models. Building on this potential, we introduce a pipeline for Guided generation of Computational Cognitive Models (GeCCo). Given task instructions, participant data, and a template function, GeCCo prompts an LLM to propose candidate models, fits proposals to held-out data, and iteratively refines them based on feedback constructed from their predictive performance. We benchmark this approach across four different cognitive domains -- decision making, learning, planning, and memory -- using three open-source LLMs, spanning different model sizes, capacities, and families. On four human behavioral data sets, the LLM generated models that consistently matched or outperformed the best domain-specific models from the cognitive science literature. Taken together, our results suggest that LLMs can generate cognitive models with conceptually plausible theories that rival -- or even surpass -- the best models from the literature across diverse task domains.
