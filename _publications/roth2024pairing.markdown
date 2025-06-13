---
layout: publication
title: 'Pairing Analogy-augmented Generation With Procedural Memory For Procedural Q&A'
authors: K Roth, Rushil Gupta, Simon Halle, Bang Liu
conference: "Arxiv"
year: 2024
bibkey: roth2024pairing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01344"}
tags: ['RAG', 'Few-Shot']
---
Large language models struggle to synthesize disparate pieces of information
into a coherent plan when approaching a complex procedural task. In this work,
we introduce a novel formalism and structure for such procedural knowledge.
Based on this formalism, we present a novel procedural knowledge dataset called
LCStep, which we created from LangChain tutorials. To leverage this procedural
knowledge to solve new tasks, we propose analogy-augmented generation (AAG),
which draws inspiration from the human ability to assimilate past experiences
to solve unfamiliar problems. AAG uses a custom procedure memory store to
retrieve and adapt specialized domain knowledge to answer new procedural tasks.
We demonstrate that AAG outperforms few-shot and RAG baselines on LCStep,
RecipeNLG, and CHAMP datasets under a pairwise LLM-based evaluation,
corroborated by human evaluation in the case of RecipeNLG.
