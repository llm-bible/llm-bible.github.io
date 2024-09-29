---
layout: publication
title: Simple Linguistic Inferences of Large Language Models (LLMs) Blind Spots and Blinds
authors: Basmov Victoria, Goldberg Yoav, Tsarfaty Reut
conference: "Arxiv"
year: 2023
bibkey: basmov2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14785"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
We evaluate LLMs language understanding capacities on simple inference tasks that most humans find trivial. Specifically we target (i) grammatically-specified entailments (ii) premises with evidential adverbs of uncertainty and (iii) monotonicity entailments. We design evaluation sets for these tasks and conduct experiments in both zero-shot and chain-of-thought setups and with multiple prompts and LLMs. The models exhibit moderate to low performance on these evaluation sets. Subsequent experiments show that embedding the premise in syntactic constructions that should preserve the entailment relations (presupposition triggers) or change them (non-factives) further confuses the models causing them to either under-predict or over-predict certain entailment labels regardless of the true relation and often disregarding the nature of the embedding context. Overall these results suggest that despite LLMs celebrated language understanding capacity even the strongest models have blindspots with respect to certain types of entailments and certain information-packaging structures act as blinds overshadowing the semantics of the embedded premise.
