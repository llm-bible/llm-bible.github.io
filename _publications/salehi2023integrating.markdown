---
layout: publication
title: 'Integrating Llms And Decision Transformers For Language Grounded Generative Quality-diversity'
authors: Achkan Salehi, Stephane Doncieux
conference: "Arxiv"
year: 2023
bibkey: salehi2023integrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.13278'}
tags: ['Agentic', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Quality-Diversity is a branch of stochastic optimization that is often
applied to problems from the Reinforcement Learning and control domains in
order to construct repertoires of well-performing policies/skills that exhibit
diversity with respect to a behavior space. Such archives are usually composed
of a finite number of reactive agents which are each associated to a unique
behavior descriptor, and instantiating behavior descriptors outside of that
coarsely discretized space is not straight-forward. While a few recent works
suggest solutions to that issue, the trajectory that is generated is not easily
customizable beyond the specification of a target behavior descriptor. We
propose to jointly solve those problems in environments where semantic
information about static scene elements is available by leveraging a Large
Language Model to augment the repertoire with natural language descriptions of
trajectories, and training a policy conditioned on those descriptions. Thus,
our method allows a user to not only specify an arbitrary target behavior
descriptor, but also provide the model with a high-level textual prompt to
shape the generated trajectory. We also propose an LLM-based approach to
evaluating the performance of such generative agents. Furthermore, we develop a
benchmark based on simulated robot navigation in a 2d maze that we use for
experimental validation.
