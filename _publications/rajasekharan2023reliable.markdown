---
layout: publication
title: 'Reliable Natural Language Understanding With Large Language Models And Answer Set Programming'
authors: Abhiramon The University Of Texas At Dallas Rajasekharan, Yankai The University Of Texas At Dallas Zeng, Parth The University Of Texas At Dallas Padalkar, Gopal The University Of Texas At Dallas Gupta
conference: "EPTCS 385 2023 pp. 274-287"
year: 2023
bibkey: rajasekharan2023reliable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.03780"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture']
---
Humans understand language by extracting information (meaning) from
sentences, combining it with existing commonsense knowledge, and then
performing reasoning to draw conclusions. While large language models (LLMs)
such as GPT-3 and ChatGPT are able to leverage patterns in the text to solve a
variety of NLP tasks, they fall short in problems that require reasoning. They
also cannot reliably explain the answers generated for a given question. In
order to emulate humans better, we propose STAR, a framework that combines LLMs
with Answer Set Programming (ASP). We show how LLMs can be used to effectively
extract knowledge -- represented as predicates -- from language. Goal-directed
ASP is then employed to reliably reason over this knowledge. We apply the STAR
framework to three different NLU tasks requiring reasoning: qualitative
reasoning, mathematical reasoning, and goal-directed conversation. Our
experiments reveal that STAR is able to bridge the gap of reasoning in NLU
tasks, leading to significant performance improvements, especially for smaller
LLMs, i.e., LLMs with a smaller number of parameters. NLU applications
developed using the STAR framework are also explainable: along with the
predicates generated, a justification in the form of a proof tree can be
produced for a given output.
