---
layout: publication
title: 'Language Model Council: Democratically Benchmarking Foundation Models On Highly Subjective Tasks'
authors: Justin Zhao, Flor Miriam Plaza-del-arco, Benjamin Genchel, Amanda Cercas Curry
conference: "Arxiv"
year: 2024
bibkey: zhao2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08598"}
tags: ['Ethics and Bias', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
As Large Language Models (LLMs) continue to evolve, evaluating them remains a
persistent challenge. Many recent evaluations use LLMs as judges to score
outputs from other LLMs, often relying on a single large model like GPT-4o.
However, using a single LLM judge is prone to intra-model bias, and many tasks
- such as those related to emotional intelligence, creative writing, and
persuasiveness - may be too subjective for a single model to judge fairly. We
introduce the Language Model Council (LMC), where a group of LLMs collaborate
to create tests, respond to them, and evaluate each other's responses to
produce a ranking in a democratic fashion. Unlike previous approaches that
focus on reducing cost or bias by using a panel of smaller models, our work
examines the benefits and nuances of a fully inclusive LLM evaluation system.
In a detailed case study on emotional intelligence, we deploy a council of 20
recent LLMs to rank each other on open-ended responses to interpersonal
conflicts. Our results show that the LMC produces rankings that are more
separable and more robust, and through a user study, we show that they are more
consistent with human evaluations than any individual LLM judge. Using all LLMs
for judging can be costly, however, so we use Monte Carlo simulations and
hand-curated sub-councils to study hypothetical council compositions and
discuss the value of the incremental LLM judge.
