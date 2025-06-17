---
layout: publication
title: 'Show Your Work: Scratchpads For Intermediate Computation With Language Models'
authors: Maxwell Nye et al.
conference: Arxiv
year: 2021
citations: 119
bibkey: nye2021show
additional_links:
- name: Paper
  url: https://arxiv.org/abs/2112.00114
tags:
- Transformer
- Few-Shot
---
Large pre-trained language models perform remarkably well on tasks that can
be done "in one pass", such as generating realistic text or synthesizing
computer programs. However, they struggle with tasks that require unbounded
multi-step computation, such as adding integers or executing programs.
Surprisingly, we find that these same models are able to perform complex
multi-step computations -- even in the few-shot regime -- when asked to perform
the operation "step by step", showing the results of intermediate computations.
In particular, we train transformers to perform multi-step computations by
asking them to emit intermediate computation steps into a "scratchpad". On a
series of increasingly complex tasks ranging from long addition to the
execution of arbitrary programs, we show that scratchpads dramatically improve
the ability of language models to perform multi-step computations.