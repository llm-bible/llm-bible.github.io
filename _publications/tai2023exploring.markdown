---
layout: publication
title: Exploring Chain45;of45;thought Style Prompting For Text45;to45;sql
authors: Tai Chang-you, Chen Ziru, Zhang Tianshu, Deng Xiang, Sun Huan
conference: "Arxiv"
year: 2023
bibkey: tai2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14215"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting']
---
In45;context learning with large language models (LLMs) has recently caught increasing attention due to its superior few45;shot performance on various tasks. However its performance on text45;to45;SQL parsing still has much room for improvement. In this paper we hypothesize that a crucial aspect of LLMs to improve for text45;to45;SQL parsing is their multi45;step reasoning ability. Thus we systematically study how to enhance LLMs reasoning ability through chain of thought (CoT) style prompting including the original chain45;of45;thought prompting (Wei et al. 2022b) and least45;to45;most prompting (Zhou et al. 2023). Our experiments demonstrate that iterative prompting as in Zhou et al. (2023) may be unnecessary for text45;to45;SQL parsing and using detailed reasoning steps tends to have more error propagation issues. Based on these findings we propose a new CoT45;style prompting method for text45;to45;SQL parsing. It brings 5.2 and 6.5 point absolute gains on the Spider development set and the Spider Realistic set respectively compared to the standard prompting method without reasoning steps; 2.4 and 1.5 point absolute gains compared to the least45;to45;most prompting method.
