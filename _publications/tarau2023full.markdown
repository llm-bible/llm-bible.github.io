---
layout: publication
title: 'Full Automation Of Goal-driven LLM Dialog Threads With And-or Recursors And Refiner Oracles'
authors: Paul Tarau
conference: "Arxiv"
year: 2023
bibkey: tarau2023full
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14077"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'Language Modeling', 'ACL', 'Prompting']
---
We automate deep step-by step reasoning in an LLM dialog thread by
recursively exploring alternatives (OR-nodes) and expanding details (AND-nodes)
up to a given depth. Starting from a single succinct task-specific initiator we
steer the automated dialog thread to stay focussed on the task by synthesizing
a prompt that summarizes the depth-first steps taken so far.
  Our algorithm is derived from a simple recursive descent implementation of a
Horn Clause interpreter, except that we accommodate our logic engine to fit the
natural language reasoning patterns LLMs have been trained on. Semantic
similarity to ground-truth facts or oracle advice from another LLM instance is
used to restrict the search space and validate the traces of justification
steps returned as answers. At the end, the unique minimal model of a generated
Horn Clause program collects the results of the reasoning process.
  As applications, we sketch implementations of consequence predictions, causal
explanations, recommendation systems and topic-focussed exploration of
scientific literature.
