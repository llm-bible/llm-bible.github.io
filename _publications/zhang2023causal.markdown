---
layout: publication
title: 'Causal Reasoning Of Entities And Events In Procedural Texts'
authors: Li Zhang, Hainiu Xu, Yue Yang, Shuyan Zhou, Weiqiu You, Manni Arora, Chris Callison-burch
conference: "Arxiv"
year: 2023
bibkey: zhang2023causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.10896"}
tags: ['Prompting', 'Model Architecture', 'GPT']
---
Entities and events are crucial to natural language reasoning and common in
procedural texts. Existing work has focused either exclusively on entity state
tracking (e.g., whether a pan is hot) or on event reasoning (e.g., whether one
would burn themselves by touching the pan), while these two tasks are often
causally related. We propose CREPE, the first benchmark on causal reasoning of
event plausibility and entity states. We show that most language models,
including GPT-3, perform close to chance at .35 F1, lagging far behind human at
.87 F1. We boost model performance to .59 F1 by creatively representing events
as programming languages while prompting language models pretrained on code. By
injecting the causal relations between entities and events as intermediate
reasoning steps in our representation, we further boost the performance to .67
F1. Our findings indicate not only the challenge that CREPE brings for language
models, but also the efficacy of code-like prompting combined with
chain-of-thought prompting for multihop event reasoning.
