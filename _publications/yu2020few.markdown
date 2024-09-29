---
layout: publication
title: Few45;shot Generative Conversational Query Rewriting
authors: Yu Shi, Liu Jiahua, Yang Jingqin, Xiong Chenyan, Bennett Paul, Gao Jianfeng, Liu Zhiyuan
conference: "Arxiv"
year: 2020
bibkey: yu2020few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.05009"}
tags: ['Applications', 'GPT', 'Model Architecture']
---
Conversational query rewriting aims to reformulate a concise conversational query to a fully specified context45;independent query that can be effectively handled by existing information retrieval systems. This paper presents a few45;shot generative approach to conversational query rewriting. We develop two methods based on rules and self45;supervised learning to generate weak supervision data using large amounts of ad hoc search sessions and to fine45;tune GPT45;2 to rewrite conversational queries. On the TREC Conversational Assistance Track our weakly supervised GPT45;2 rewriter improves the state45;of45;the45;art ranking accuracy by 1237; only using very limited amounts of manual query rewrites. In the zero45;shot learning setting the rewriter still gives a comparable result to previous state45;of45;the45;art systems. Our analyses reveal that GPT45;2 effectively picks up the task syntax and learns to capture context dependencies even for hard cases that involve group references and long45;turn dependencies.
