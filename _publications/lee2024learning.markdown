---
layout: publication
title: 'Learning To Reduce: Optimal Representations Of Structured Data In Prompting Large Language Models'
authors: Younghun Lee, Sungchul Kim, Tong Yu, Ryan A. Rossi, Xiang Chen
conference: "Arxiv"
year: 2024
bibkey: lee2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14195"}
tags: ['Prompting', 'Agentic', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have been widely used as general-purpose AI
agents showing comparable performance on many downstream tasks. However,
existing work shows that it is challenging for LLMs to integrate structured
data (e.g. KG, tables, DBs) into their prompts; LLMs need to either understand
long text data or select the most relevant evidence prior to inference, and
both approaches are not trivial.
  In this paper, we propose a framework, Learning to Reduce, that fine-tunes a
language model to generate a reduced version of an input context, given a task
description and context input. The model learns to reduce the input context
using On-Policy Reinforcement Learning and aims to improve the reasoning
performance of a fixed LLM. Experimental results illustrate that our model not
only achieves comparable accuracies in selecting the relevant evidence from an
input context, but also shows generalizability on different datasets. We
further show that our model helps improve the LLM's performance on downstream
tasks especially when the context is long.
