---
layout: publication
title: 'Bigo(bench) -- Can Llms Generate Code With Controlled Time And Space Complexity?'
authors: Pierre Chambon, Baptiste Roziere, Benoit Sagot, Gabriel Synnaeve
conference: "Arxiv"
year: 2025
bibkey: chambon2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15242"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning']
---
We introduce BigO(Bench), a novel coding benchmark designed to evaluate the
capabilities of generative language models in understanding and generating code
with specified time and space complexities. This benchmark addresses the gap in
current evaluations that often overlook the ability of models to comprehend and
produce code constrained by computational complexity. BigO(Bench) includes
tooling to infer the algorithmic complexity of any Python function from
profiling measurements, including human- or LLM-generated solutions.
BigO(Bench) also includes of set of 3,105 coding problems and 1,190,250
solutions from Code Contests annotated with inferred (synthetic) time and space
complexity labels from the complexity framework, as well as corresponding
runtime and memory footprint values for a large set of input sizes. We present
results from evaluating multiple state-of-the-art language models on this
benchmark, highlighting their strengths and weaknesses in handling complexity
requirements. In particular, token-space reasoning models are unrivaled in code
generation but not in complexity understanding, hinting that they may not
generalize well to tasks for which no reward was given at training time.
