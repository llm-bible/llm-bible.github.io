---
layout: publication
title: 'Omulet: Orchestrating Multiple Tools For Practicable Conversational Recommendation'
authors: Se-eun Yoon, Xiaokai Wei, Yexi Jiang, Rachit Pareek, Frank Ong, Kevin Gao, Julian Mcauley, Michelle Gong
conference: "Arxiv"
year: 2024
bibkey: yoon2024orchestrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19352'}
tags: ['Tools']
---
In this paper, we present a systematic effort to design, evaluate, and
implement a realistic conversational recommender system (CRS). The objective of
our system is to allow users to input free-form text to request
recommendations, and then receive a list of relevant and diverse items. While
previous work on synthetic queries augments large language models (LLMs) with
1-3 tools, we argue that a more extensive toolbox is necessary to effectively
handle real user requests. As such, we propose a novel approach that equips
LLMs with over 10 tools, providing them access to the internal knowledge base
and API calls used in production. We evaluate our model on a dataset of real
users and show that it generates relevant, novel, and diverse recommendations
compared to vanilla LLMs. Furthermore, we conduct ablation studies to
demonstrate the effectiveness of using the full range of tools in our toolbox.
We share our designs and lessons learned from deploying the system for internal
alpha release. Our contribution is the addressing of all four key aspects of a
practicable CRS: (1) real user requests, (2) augmenting LLMs with a wide
variety of tools, (3) extensive evaluation, and (4) deployment insights.
