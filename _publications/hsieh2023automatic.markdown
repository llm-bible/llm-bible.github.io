---
layout: publication
title: 'Automatic Engineering Of Long Prompts'
authors: Cho-jui Hsieh, Si Si, Felix X. Yu, Inderjit S. Dhillon
conference: "Arxiv"
year: 2023
bibkey: hsieh2023automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.10117'}
tags: ['RAG', 'Efficiency and Optimization', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
solving complex open-domain tasks, guided by comprehensive instructions and
demonstrations provided in the form of prompts. However, these prompts can be
lengthy, often comprising hundreds of lines and thousands of tokens, and their
design often requires considerable human effort. Recent research has explored
automatic prompt engineering for short prompts, typically consisting of one or
a few sentences. However, the automatic design of long prompts remains a
challenging problem due to its immense search space. In this paper, we
investigate the performance of greedy algorithms and genetic algorithms for
automatic long prompt engineering. We demonstrate that a simple greedy approach
with beam search outperforms other methods in terms of search efficiency.
Moreover, we introduce two novel techniques that utilize search history to
enhance the effectiveness of LLM-based mutation in our search algorithm. Our
results show that the proposed automatic long prompt engineering algorithm
achieves an average of 9.2% accuracy gain on eight tasks in Big Bench Hard,
highlighting the significance of automating prompt designs to fully harness the
capabilities of LLMs.
