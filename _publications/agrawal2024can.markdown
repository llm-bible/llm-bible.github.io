---
layout: publication
title: Can Llms Perform Structured Graph Reasoning
authors: Agrawal Palaash, Vasania Shavak, Tan Cheston
conference: "Arxiv"
year: 2024
bibkey: agrawal2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01805"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Pretrained Large Language Models (LLMs) have demonstrated various reasoning capabilities through language45;based prompts alone particularly in unstructured task settings (tasks purely based on language semantics). However LLMs often struggle with structured tasks because of the inherent incompatibility of input representation. Reducing structured tasks to uni45;dimensional language semantics often renders the problem trivial. Keeping the trade45;off between LLM compatibility and structure complexity in mind we design various graph reasoning tasks as a proxy to semi45;structured tasks in this paper in order to test the ability to navigate through representations beyond plain text in various LLMs. Particularly we design 10 distinct problems of graph traversal each representing increasing levels of complexity and benchmark 5 different instruct45;finetuned LLMs (GPT45;4 GPT45;3.5 Claude45;2 Llama45;2 and Palm45;2) on the aforementioned tasks. Further we analyse the performance of models across various settings such as varying sizes of graphs as well as different forms of k45;shot prompting. We highlight various limitations biases and properties of LLMs through this benchmarking process such as an inverse relation to the average degrees of freedom of traversal per node in graphs the overall negative impact of k45;shot prompting on graph reasoning tasks and a positive response bias which prevents LLMs from identifying the absence of a valid solution. Finally we introduce a new prompting technique specially designed for graph traversal tasks (PathCompare) which demonstrates a notable increase in the performance of LLMs in comparison to standard prompting techniques such as Chain45;of45;Thought (CoT).
