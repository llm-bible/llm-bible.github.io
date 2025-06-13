---
layout: publication
title: 'Misconfidence-based Demonstration Selection For LLM In-context Learning'
authors: Shangqing Georgia Institute Of Technology Xu, Chao Georgia Institute Of Technology Zhang
conference: "Arxiv"
year: 2024
bibkey: xu2024misconfidence
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.06301'}
tags: ['ACL', 'In-Context Learning', 'RAG', 'Tools', 'Prompting', 'TACL']
---
In-context learning with large language models (LLMs) excels at adapting to
various tasks rapidly. However, its success hinges on carefully selecting
demonstrations, which remains an obstacle in practice. Current approaches to
this problem either rely on hard-to-acquire external supervision or require
frequent interactions with LLMs, resulting in high costs. We propose a new
method called In-Context Reflection (ICR) to overcome these challenges. ICR
strategically selects demonstrations to reduce the discrepancy between the
LLM's outputs and the actual input-output mappings. Specifically, ICR starts
with a random set of initial demonstrations, then iteratively refines it. In
each step, it analyzes a pool of candidate examples and identifies the ones
most likely to challenge the LLM's current understanding, measured by a new
metric called misconfidence. These most confusing examples are then selected to
replace the less informative demonstrations in the current set. Our
comprehensive evaluation across five diverse datasets encompassing 13 subtasks
shows the efficacy of ICR. Compared to existing methods, ICR achieves an
average performance boost of 4%, while demonstrating remarkable cross-task
generalization capabilities.
