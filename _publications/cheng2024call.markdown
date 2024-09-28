---
layout: publication
title: Call Me When Necessary LLMs can Efficiently and Faithfully Reason over Structured Environments
authors: Cheng Sitao, Zhuang Ziyuan, Xu Yong, Yang Fangkai, Zhang Chaoyun, Qin Xiaoting, Huang Xiang, Chen Ling, Lin Qingwei, Zhang Dongmei, Rajmohan Saravan, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: cheng2024call
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08593"}
  - {name: "Code", url: "https://aka.ms/readi"}
tags: ['ARXIV', 'Applications', 'Has Code', 'LLM', 'RAG', 'Tools']
---
Large Language Models (LLMs) have shown potential in reasoning over structured environments e.g. knowledge graph and table. Such tasks typically require multi-hop reasoning i.e. match natural language utterance with instances in the environment. Previous methods leverage LLMs to incrementally build a reasoning path where the LLMs either invoke tools or pick up schemas by step-by-step interacting with the environment. We propose Reasoning-Path-Editing (Readi) a novel framework where LLMs can efficiently and faithfully reason over structured environments. In Readi LLMs initially generate a reasoning path given a query and edit the path only when necessary. We instantiate the path on structured environments and provide feedback to edit the path if anything goes wrong. Experimental results on three KGQA and two TableQA datasets show the effectiveness of Readi significantly surpassing previous LLM-based methods (by 9.1 Hit@1 on WebQSP 12.4 on MQA-3H and 9.5 on WTQ) comparable with state-of-the-art fine-tuned methods (67 on CWQ and 74.7 on WebQSP) and substantially boosting the vanilla LLMs (by 14.9 on CWQ). Our code will be available on https://aka.ms/readi.
