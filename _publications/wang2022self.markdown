---
layout: publication
title: Self45;consistency Improves Chain Of Thought Reasoning In Language Models
authors: Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou
conference: "Arxiv"
year: 2022
bibkey: wang2022self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2203.11171v4"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Chain45;of45;thought prompting combined with pre45;trained large language models has achieved encouraging results on complex reasoning tasks. In this paper we propose a new decoding strategy self45;consistency to replace the naive greedy decoding used in chain45;of45;thought prompting. It first samples a diverse set of reasoning paths instead of only taking the greedy one and then selects the most consistent answer by marginalizing out the sampled reasoning paths. Self45;consistency leverages the intuition that a complex reasoning problem typically admits multiple different ways of thinking leading to its unique correct answer. Our extensive empirical evaluation shows that self45;consistency boosts the performance of chain45;of45;thought prompting with a striking margin on a range of popular arithmetic and commonsense reasoning benchmarks including GSM8K (+17.937;) SVAMP (+11.037;) AQuA (+12.237;) StrategyQA (+6.437;) and ARC45;challenge (+3.937;).
