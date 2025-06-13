---
layout: publication
title: 'Contextualize-then-aggregate: Circuits For In-context Learning In Gemma-2 2B'
authors: Aleksandra Bakalova, Yana Veitsman, Xinting Huang, Michael Hahn
conference: "Arxiv"
year: 2025
bibkey: bakalova2025contextualize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00132"}
tags: ['Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) is an intriguing ability of large language models
(LLMs). Despite a substantial amount of work on its behavioral aspects and how
it emerges in miniature setups, it remains unclear which mechanism assembles
task information from the individual examples in a fewshot prompt. We use
causal interventions to identify information flow in Gemma-2 2B for five
naturalistic ICL tasks. We find that the model infers task information using a
two-step strategy we call contextualize-then-aggregate: In the lower layers,
the model builds up representations of individual fewshot examples, which are
contextualized by preceding examples through connections between fewshot input
and output tokens across the sequence. In the higher layers, these
representations are aggregated to identify the task and prepare prediction of
the next output. The importance of the contextualization step differs between
tasks, and it may become more important in the presence of ambiguous examples.
Overall, by providing rigorous causal analysis, our results shed light on the
mechanisms through which ICL happens in language models.
