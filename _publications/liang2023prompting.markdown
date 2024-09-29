---
layout: publication
title: Prompting Large Language Models With Chain45;of45;thought For Few45;shot Knowledge Base Question Generation
authors: Liang Yuanyuan, Wang Jianing, Zhu Hanlun, Wang Lei, Qian Weining, Lan Yunshi
conference: "Arxiv"
year: 2023
bibkey: liang2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08395"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
The task of Question Generation over Knowledge Bases (KBQG) aims to convert a logical form into a natural language question. For the sake of expensive cost of large45;scale question annotation the methods of KBQG under low45;resource scenarios urgently need to be developed. However current methods heavily rely on annotated data for fine45;tuning which is not well45;suited for few45;shot question generation. The emergence of Large Language Models (LLMs) has shown their impressive generalization ability in few45;shot tasks. Inspired by Chain45;of45;Thought (CoT) prompting which is an in45;context learning strategy for reasoning we formulate KBQG task as a reasoning problem where the generation of a complete question is splitted into a series of sub45;question generation. Our proposed prompting method KQG45;CoT first retrieves supportive logical forms from the unlabeled data pool taking account of the characteristics of the logical form. Then we write a prompt to explicit the reasoning chain of generating complicated questions based on the selected demonstrations. To further ensure prompt quality we extend KQG45;CoT into KQG45;CoT+ via sorting the logical forms by their complexity. We conduct extensive experiments over three public KBQG datasets. The results demonstrate that our prompting method consistently outperforms other prompting baselines on the evaluated datasets. Remarkably our KQG45;CoT+ method could surpass existing few45;shot SoTA results of the PathQuestions dataset by 18.25 10.72 and 10.18 absolute points on BLEU45;4 METEOR and ROUGE45;L respectively.
