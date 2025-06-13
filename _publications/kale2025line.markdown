---
layout: publication
title: 'Line Of Duty: Evaluating LLM Self-knowledge Via Consistency In Feasibility Boundaries'
authors: Sahil Kale, Vijaykant Nadadur
conference: "Arxiv"
year: 2025
bibkey: kale2025line
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11256"}
  - {name: "Code", url: "https://github.com/knowledge-verse-ai/LLM-Self_Knowledge_Eval"}
tags: ['Has Code', 'Model Architecture', 'GPT', 'Merging']
---
As LLMs grow more powerful, their most profound achievement may be
recognising when to say "I don't know". Existing studies on LLM self-knowledge
have been largely constrained by human-defined notions of feasibility, often
neglecting the reasons behind unanswerability by LLMs and failing to study
deficient types of self-knowledge. This study aims to obtain intrinsic insights
into different types of LLM self-knowledge with a novel methodology: allowing
them the flexibility to set their own feasibility boundaries and then analysing
the consistency of these limits. We find that even frontier models like GPT-4o
and Mistral Large are not sure of their own capabilities more than 80% of the
time, highlighting a significant lack of trustworthiness in responses. Our
analysis of confidence balance in LLMs indicates that models swing between
overconfidence and conservatism in feasibility boundaries depending on task
categories and that the most significant self-knowledge weaknesses lie in
temporal awareness and contextual understanding. These difficulties in
contextual comprehension additionally lead models to question their operational
boundaries, resulting in considerable confusion within the self-knowledge of
LLMs. We make our code and results available publicly at
https://github.com/knowledge-verse-ai/LLM-Self_Knowledge_Eval
