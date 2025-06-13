---
layout: publication
title: 'A Framework For Evaluating Llms Under Task Indeterminacy'
authors: Luke Guerdan, Hanna Wallach, Solon Barocas, Alexandra Chouldechova
conference: "Arxiv"
year: 2024
bibkey: guerdan2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13760"}
tags: ['Tools', 'Reinforcement Learning']
---
Large language model (LLM) evaluations often assume there is a single correct
response -- a gold label -- for each item in the evaluation corpus. However,
some tasks can be ambiguous -- i.e., they provide insufficient information to
identify a unique interpretation -- or vague -- i.e., they do not clearly
indicate where to draw the line when making a determination. Both ambiguity and
vagueness can cause task indeterminacy -- the condition where some items in the
evaluation corpus have more than one correct response. In this paper, we
develop a framework for evaluating LLMs under task indeterminacy. Our framework
disentangles the relationships between task specification, human ratings, and
LLM responses in the LLM evaluation pipeline. Using our framework, we conduct a
synthetic experiment showing that evaluations that use the "gold label"
assumption underestimate the true performance. We also provide a method for
estimating an error-adjusted performance interval given partial knowledge about
indeterminate items in the evaluation corpus. We conclude by outlining
implications of our work for the research community.
