---
layout: publication
title: "Hierarchical Prompting Assists Large Language Model On Web Navigation"
authors: Sridhar Abishek, Lo Robert, Xu Frank F., Zhu Hao, Zhou Shuyan
conference: "Arxiv"
year: 2023
bibkey: sridhar2023hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14257"}
tags: ['Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) struggle on processing complicated observations in interactive decision making tasks. To alleviate this issue we propose a simple hierarchical prompting approach. Diverging from previous prompting approaches that always put the full observation (e.g. a web page) to the prompt we propose to first construct an action-aware observation which is more condensed and relevant with a dedicated SUMMARIZER prompt. The ACTOR prompt then predicts the next action based on the summarized observation. While our method has broad applicability we particularly demonstrate its efficacy in the complex domain of web navigation where a full observation often contains redundant and irrelevant information. Our approach outperforms the previous state-of-the-art prompting mechanics by 6.237; on task success rate demonstrating its potential on interactive decision making tasks with long observation traces.
