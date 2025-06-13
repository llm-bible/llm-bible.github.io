---
layout: publication
title: 'Large Language Models As A Tool For Mining Object Knowledge'
authors: Hannah Youngeun An, Lenhart K. Schubert
conference: "Arxiv"
year: 2024
bibkey: an2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12959"}
tags: ['Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Few-Shot', 'Prompting']
---
Commonsense knowledge is essential for machines to reason about the world.
Large language models (LLMs) have demonstrated their ability to perform almost
human-like text generation. Despite this success, they fall short as
trustworthy intelligent systems, due to the opacity of the basis for their
answers and a tendency to confabulate facts when questioned about obscure
entities or technical domains. We hypothesize, however, that their general
knowledge about objects in the everyday world is largely sound. Based on that
hypothesis, this paper investigates LLMs' ability to formulate explicit
knowledge about common physical artifacts, focusing on their parts and
materials. Our work distinguishes between the substances that comprise an
entire object and those that constitute its parts\\(\unicode\{x2014\}\\)a previously
underexplored distinction in knowledge base construction. Using few-shot with
five in-context examples and zero-shot multi-step prompting, we produce a
repository of data on the parts and materials of about 2,300 objects and their
subtypes. Our evaluation demonstrates LLMs' coverage and soundness in
extracting knowledge. This contribution to knowledge mining should prove useful
to AI research on reasoning about object structure and composition and serve as
an explicit knowledge source (analogous to knowledge graphs) for LLMs
performing multi-hop question answering.
