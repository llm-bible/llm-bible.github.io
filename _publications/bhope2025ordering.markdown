---
layout: publication
title: 'Optiseq: Ordering Examples On-the-fly For In-context Learning'
authors: Rahul Atul Bhope, Praveen Venkateswaran, K. R. Jayaram, Vatche Isahagian, Vinod Muthusamy, Nalini Venkatasubramanian
conference: "Arxiv"
year: 2025
bibkey: bhope2025ordering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15030"}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'RAG', 'Prompting', 'In-Context Learning']
---
Developers using LLMs and LLM-based agents in their applications have
provided plenty of anecdotal evidence that in-context-learning (ICL) is
fragile. In this paper, we show that in addition to the quantity and quality of
examples, the order in which the in-context examples are listed in the prompt
affects the output of the LLM and, consequently, their performance. While prior
work has explored improving ICL through dataset-dependent techniques, we
introduce OptiSeq, a purely inference-time, dataset-free optimization method
that efficiently determines the best example order. OptiSeq leverages log
probabilities of LLM-generated outputs to systematically prune the search space
of possible orderings and recommend the best order(s) by distinguishing
orderings that yield high levels of accuracy and those that underperform.
Extensive empirical evaluation on multiple LLMs, datasets, and prompts
demonstrate that OptiSeq improves accuracy by 5.5 - 10.5 percentage points
across multiple tasks.
