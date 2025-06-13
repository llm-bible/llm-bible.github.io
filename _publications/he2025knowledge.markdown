---
layout: publication
title: 'Knowledge Updating? No More Model Editing! Just Selective Contextual Reasoning'
authors: Guoxiu He, Xin Song, Aixin Sun
conference: "Arxiv"
year: 2025
bibkey: he2025knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05212'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization']
---
As real-world knowledge evolves, the information embedded within large
language models (LLMs) can become outdated, inadequate, or erroneous. Model
editing has emerged as a prominent approach for updating LLMs' knowledge with
minimal computational costs and parameter changes. This approach typically
identifies and adjusts specific model parameters associated with newly acquired
knowledge. However, existing methods often underestimate the adverse effects
that parameter modifications can have on broadly distributed knowledge. More
critically, post-edit LLMs frequently struggle with multi-hop reasoning and
continuous knowledge updates. Although various studies have discussed these
shortcomings, there is a lack of comprehensive evaluation. In this paper, we
provide an evaluation of ten model editing methods along four dimensions:
reliability, generalization, locality, and portability. Results confirm that
all ten popular model editing methods show significant shortcomings across
multiple dimensions, suggesting model editing is less promising. We then
propose a straightforward method called Selective Contextual Reasoning (SCR),
for knowledge updating. SCR does not modify model parameters but harnesses
LLM's inherent contextual reasoning capabilities utilizing the updated
knowledge pieces. Under SCR, an LLM first assesses whether an incoming query
falls within the scope of an external knowledge base. If it does, the relevant
external knowledge texts are contextualized to enhance reasoning; otherwise,
the query is answered directly. We evaluate SCR against the ten model editing
methods on two counterfactual datasets with three backbone LLMs. Empirical
results confirm the effectiveness and efficiency of contextual reasoning for
knowledge updating.
