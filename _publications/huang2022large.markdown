---
layout: publication
title: Large Language Models Can Self45;improve
authors: Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han
conference: "Arxiv"
year: 2022
bibkey: huang2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.11610v2"}
tags: ['Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have achieved excellent performances in various tasks. However fine45;tuning an LLM requires extensive supervision. Human on the other hand may improve their reasoning abilities by self45;thinking without external inputs. In this work we demonstrate that an LLM is also capable of self45;improving with only unlabeled datasets. We use a pre45;trained LLM to generate high45;confidence rationale45;augmented answers for unlabeled questions using Chain45;of45;Thought prompting and self45;consistency and fine45;tune the LLM using those self45;generated solutions as target outputs. We show that our approach improves the general reasoning ability of a 540B45;parameter LLM (74.437;45;82.137; on GSM8K 78.237;45;83.037; on DROP 90.037;45;94.437; on OpenBookQA and 63.437;45;67.937; on ANLI45;A3) and achieves state45;of45;the45;art45;level performance without any ground truth label. We conduct ablation studies and show that fine45;tuning on reasoning is critical for self45;improvement.
