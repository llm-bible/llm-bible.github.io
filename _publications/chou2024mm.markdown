---
layout: publication
title: 'MM-R\(^3\): On (in-)consistency Of Multi-modal Large Language Models (mllms)'
authors: Shih-han Chou, Shivam Chandhok, James J. Little, Leonid Sigal
conference: "Arxiv"
year: 2024
bibkey: chou2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04778"}
tags: ['Applications', 'RAG', 'Security', 'Multimodal Models', 'Prompting']
---
With the advent of Large Language Models (LLMs) and Multimodal
(Visio-lingual) LLMs, a flurry of research has emerged, analyzing the
performance of such models across a diverse array of tasks. While most studies
focus on evaluating the capabilities of state-of-the-art (SoTA) MLLM models
through task accuracy (e.g., Visual Question Answering, grounding) across
various datasets, our work explores the related but complementary aspect of
consistency - the ability of an MLLM model to produce semantically similar or
identical responses to semantically similar queries. We note that consistency
is a fundamental prerequisite (necessary but not sufficient condition) for
robustness and trust in MLLMs. Humans, in particular, are known to be highly
consistent (even if not always accurate) in their responses, and consistency is
inherently expected from AI systems. Armed with this perspective, we propose
the MM-R\\(^3\\) benchmark, which analyses the performance in terms of consistency
and accuracy in SoTA MLLMs with three tasks: Question Rephrasing, Image
Restyling, and Context Reasoning. Our analysis reveals that consistency does
not always align with accuracy, indicating that models with higher accuracy are
not necessarily more consistent, and vice versa. Furthermore, we propose a
simple yet effective mitigation strategy in the form of an adapter module
trained to minimize inconsistency across prompts. With our proposed strategy,
we are able to achieve absolute improvements of 5.7% and 12.5%, on average on
widely used MLLMs such as BLIP-2 and LLaVa 1.5M in terms of consistency over
their existing counterparts.
