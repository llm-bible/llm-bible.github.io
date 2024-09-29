---
layout: publication
title: 'Comparing Bad Apples To Good Oranges: Aligning Large Language Models Via Joint Preference Optimization'
authors: Bansal Hritik, Suvarna Ashima, Bhatt Gantavya, Peng Nanyun, Chang Kai-wei, Grover Aditya
conference: "Arxiv"
year: 2024
bibkey: bansal2024comparing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00530"}
  - {name: "Code", url: "https://github.com/Hritikbansal/dove"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning']
---
A common technique for aligning large language models (LLMs) relies on acquiring human preferences by comparing multiple generations conditioned on a fixed context. This only leverages the pairwise comparisons when the generations are placed in an identical context. However such conditional rankings often fail to capture the complex and multidimensional aspects of human preferences. In this work we revisit the traditional paradigm of preference acquisition and propose a new axis that is based on eliciting preferences jointly over the instruction-response pairs. While prior preference optimizations are designed for conditional ranking protocols (e.g. DPO) our proposed preference acquisition protocol introduces DOVE a new preference optimization objective that upweights the joint probability of the chosen instruction-response pair over the rejected instruction-response pair. Interestingly we find that the LLM trained with joint instruction-response preference data using DOVE outperforms the LLM trained with DPO by 5.237; and 3.337; win-rate for the summarization and open-ended dialogue datasets respectively. Our findings reveal that joint preferences over instruction and response pairs can significantly enhance the alignment of LLMs by tapping into a broader spectrum of human preference elicitation. The data and code is available at https://github.com/Hritikbansal/dove."
