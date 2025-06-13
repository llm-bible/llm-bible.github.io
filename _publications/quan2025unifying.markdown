---
layout: publication
title: 'PEIRCE: Unifying Material And Formal Reasoning Via Llm-driven Neuro-symbolic Refinement'
authors: Xin Quan, Marco Valentino, Danilo S. Carvalho, Dhairya Dalal, André Freitas
conference: "Arxiv"
year: 2025
bibkey: quan2025unifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04110'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pre-Training']
---
A persistent challenge in AI is the effective integration of material and
formal inference - the former concerning the plausibility and contextual
relevance of arguments, while the latter focusing on their logical and
structural validity. Large Language Models (LLMs), by virtue of their extensive
pre-training on large textual corpora, exhibit strong capabilities in material
inference. However, their reasoning often lacks formal rigour and
verifiability. At the same time, LLMs' linguistic competence positions them as
a promising bridge between natural and formal languages, opening up new
opportunities for combining these two modes of reasoning. In this paper, we
introduce PEIRCE, a neuro-symbolic framework designed to unify material and
formal inference through an iterative conjecture-criticism process. Within this
framework, LLMs play the central role of generating candidate solutions in
natural and formal languages, which are then evaluated and refined via
interaction with external critique models. These critiques include symbolic
provers, which assess formal validity, as well as soft evaluators that measure
the quality of the generated arguments along linguistic and epistemic
dimensions such as plausibility, coherence, and parsimony. While PEIRCE is a
general-purpose framework, we demonstrate its capabilities in the domain of
natural language explanation generation - a setting that inherently demands
both material adequacy and formal correctness.
