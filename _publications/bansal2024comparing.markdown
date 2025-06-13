---
layout: publication
title: 'Comparing Bad Apples To Good Oranges: Aligning Large Language Models Via Joint Preference Optimization'
authors: Hritik Bansal, Ashima Suvarna, Gantavya Bhatt, Nanyun Peng, Kai-wei Chang, Aditya Grover
conference: "Arxiv"
year: 2024
bibkey: bansal2024comparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00530"}
  - {name: "Code", url: "https://github.com/Hritikbansal/dove"}
tags: ['Efficiency and Optimization', 'Has Code', 'Applications', 'Reinforcement Learning']
---
A common technique for aligning large language models (LLMs) relies on
acquiring human preferences by comparing multiple generations conditioned on a
fixed context. This method, however, relies solely on pairwise comparisons,
where the generations are evaluated within an identical context. While
effective to such conditional preferences often fail to encompass the nuanced
and multidimensional nature of human preferences. In this work, we revisit the
traditional paradigm of preference acquisition and propose a new axis based on
eliciting preferences jointly over the instruction-response pairs. Unlike prior
preference optimizations, which are designed for conditional ranking protocols
(e.g., DPO), we propose Joint Preference Optimization (JPO), a new preference
optimization objective that upweights the joint probability of the chosen
instruction-response pair over the rejected instruction-response pair.
Interestingly, LLMs trained with joint instruction-response preference data
using JPO outperform LLM trained with DPO by \\(5.2%\\) and \\(3.3%\\) win-rate for
summarization and open-ended dialogue datasets, respectively. Our findings
reveal that joint preferences over instruction and response pairs can
significantly enhance the alignment of LLMs by tapping into a broader spectrum
of human preference elicitation. The data and code is available at
https://github.com/Hritikbansal/dove.
