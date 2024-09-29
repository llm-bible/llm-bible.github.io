---
layout: publication
title: Pad Program45;aided Distillation Can Teach Small Models Reasoning Better Than Chain45;of45;thought Fine45;tuning
authors: Zhu Xuekai, Qi Biqing, Zhang Kaiyan, Long Xinwei, Lin Zhouhan, Zhou Bowen
conference: "Arxiv"
year: 2023
bibkey: zhu2023program
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13888"}
  - {name: "Code", url: "https://github.com/Xuekai&#45;Zhu/pad"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Training Techniques']
---
While large language models (LLMs) excel in various natural language processing tasks their huge size and the inaccessibility of parameters present challenges for practical deployment. Previous studies try to distill task45;specific ability from LLMs to smaller models using data synthesis and chain45;of45;thought (CoT) fine45;tuning. However synthetic CoT data often contains faulty reasoning which deteriorates the quality of distillation especially in reasoning capabilities. In this work we propose Program45;aided Distillation (PaD) which introduces reasoning programs to suppress the errors in distilled data and thus achieves better distillation quality for reasoning tasks. In PaD we utilize the reasoning program to substitute the CoT allowing automated error checking of synthetic data. Further through error injecting and further training the small distilling model could iteratively self45;refine the reasoning. Moreover we conduct a step45;wise beam search by step45;by45;step verifying to acquire more exact reasoning chains. We evaluate PaD on arithmetic reasoning symbolic reasoning and general ability. Experimental results demonstrate that smaller models using PaD can not only outperform certain LLMs~(e.g. LLaMA45;1 13B) but also achieve strong improvement over baselines with a significantly smaller scale of parameters and data. The source code is publicly available at https://github.com/Xuekai&#45;Zhu/pad.
