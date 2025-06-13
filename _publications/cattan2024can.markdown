---
layout: publication
title: 'Can Few-shot Work In Long-context? Recycling The Context To Generate Demonstrations'
authors: Arie Cattan, Alon Jacovi, Alex Fabrikant, Jonathan Herzig, Roee Aharoni, Hannah Rashkin, Dror Marcus, Avinatan Hassidim, Yossi Matias, Idan Szpektor, Avi Caciularu
conference: "Arxiv"
year: 2024
bibkey: cattan2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13632'}
tags: ['Few-Shot', 'Prompting', 'RAG']
---
Despite recent advancements in Large Language Models (LLMs), their
performance on tasks involving long contexts remains sub-optimal. In-Context
Learning (ICL) with few-shot examples may be an appealing solution to enhance
LLM performance in this scenario; However, na\"ively adding ICL examples with
long context introduces challenges, including substantial token overhead added
for each few-shot example and context mismatch between the demonstrations and
the target query. In this work, we propose to automatically generate few-shot
examples for long context QA tasks by recycling contexts. Specifically, given a
long input context (1-3k tokens) and a query, we generate additional
query-output pairs from the given context as few-shot examples, while
introducing the context only once. This ensures that the demonstrations are
leveraging the same context as the target query while only adding a small
number of tokens to the prompt. We further enhance each demonstration by
instructing the model to explicitly identify the relevant paragraphs before the
answer, which improves performance while providing fine-grained attribution to
the answer source. We apply our method on multiple LLMs and obtain substantial
improvements (+16 absolute points on average across models) on various QA
datasets with long context, especially when the answer lies within the middle
of the context. Surprisingly, despite introducing only single-hop ICL examples,
LLMs also successfully generalize to multi-hop long-context QA using our
approach.
