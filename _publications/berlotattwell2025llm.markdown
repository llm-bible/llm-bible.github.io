---
layout: publication
title: 'LLM Library Learning Fails: A Lego-prover Case Study'
authors: Ian Berlot-attwell, Frank Rudzicz, Xujie Si
conference: "Arxiv"
year: 2025
bibkey: berlotattwell2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03048"}
tags: ['RAG', 'Tools', 'Prompting']
---
Recent advancements in the coding, reasoning, and tool-using abilities of
LLMs have spurred interest in library learning (i.e., online learning through
the creation, storage, and retrieval of reusable and composable functions,
knowledge, checklists, or lemmas). Such systems often promise improved task
performance through the automatic creation of broadly applicable tools, as well
as superior computational performance through the caching of reasoning (i.e.,
the storage of generated tools). However, we find strong reason to be
skeptical. We perform a deep dive into one such system, LEGO-Prover, which
purports to learn reusable lemmas for mathematical reasoning. We find no
evidence of the direct reuse of learned lemmas, and find evidence against the
soft reuse of learned lemmas (i.e., reuse by modifying relevant examples).
Crucially, we find that LEGO-Prover does not in fact improve over the simple
baseline of prompting the model - the improvements in task accuracy vanish once
computational cost is accounted for. Our findings suggest that serious
misconceptions exist as to the effectiveness of these techniques, that a
serious re-examination of the state of LLM-based library learning is required,
and that we require much stronger standards for evaluation including
behavioural analysis and ensuring that an equal computational budget is used
for baselines.
