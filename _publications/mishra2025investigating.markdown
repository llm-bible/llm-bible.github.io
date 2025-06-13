---
layout: publication
title: 'Investigating The Shortcomings Of Llms In Step-by-step Legal Reasoning'
authors: Venkatesh Mishra, Bimsara Pathiraja, Mihir Parmar, Sat Chidananda, Jayanth Srinivasa, Gaowen Liu, Ali Payani, Chitta Baral
conference: "Arxiv"
year: 2025
bibkey: mishra2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05675"}
tags: ['Tools', 'Prompting']
---
Reasoning abilities of LLMs have been a key focus in recent years. One
challenging reasoning domain with interesting nuances is legal reasoning, which
requires careful application of rules, and precedents while balancing deductive
and analogical reasoning, and conflicts between rules. Although there have been
a few works on using LLMs for legal reasoning, their focus has been on overall
accuracy. In this paper, we dig deeper to do a step-by-step analysis and figure
out where they commit errors. We use the college-level Multiple Choice
Question-Answering (MCQA) task from the \textit\{Civil Procedure\} dataset and
propose a new error taxonomy derived from initial manual analysis of reasoning
chains with respect to several LLMs, including two objective measures:
soundness and correctness scores. We then develop an LLM-based automated
evaluation framework to identify reasoning errors and evaluate the performance
of LLMs. The computation of soundness and correctness on the dataset using the
auto-evaluator framework reveals several interesting insights. Furthermore, we
show that incorporating the error taxonomy as feedback in popular prompting
techniques marginally increases LLM performance. Our work will also serve as an
evaluation framework that can be used in detailed error analysis of reasoning
chains for logic-intensive complex tasks.
