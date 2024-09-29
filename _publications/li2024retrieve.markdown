---
layout: publication
title: Recall Retrieve And Reason Towards Better In45;context Relation Extraction
authors: Li Guozheng, Wang Peng, Ke Wenjun, Guo Yikai, Ji Ke, Shang Ziyu, Liu Jiajun, Xu Zijie
conference: "Arxiv"
year: 2024
bibkey: li2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17809"}
tags: ['Language Modeling', 'Prompting', 'Tools', 'Training Techniques']
---
Relation extraction (RE) aims to identify relations between entities mentioned in texts. Although large language models (LLMs) have demonstrated impressive in45;context learning (ICL) abilities in various tasks they still suffer from poor performances compared to most supervised fine45;tuned RE methods. Utilizing ICL for RE with LLMs encounters two challenges (1) retrieving good demonstrations from training examples and (2) enabling LLMs exhibit strong ICL abilities in RE. On the one hand retrieving good demonstrations is a non45;trivial process in RE which easily results in low relevance regarding entities and relations. On the other hand ICL with an LLM achieves poor performance in RE while RE is different from language modeling in nature or the LLM is not large enough. In this work we propose a novel recall45;retrieve45;reason RE framework that synergizes LLMs with retrieval corpora (training examples) to enable relevant retrieving and reliable in45;context reasoning. Specifically we distill the consistently ontological knowledge from training datasets to let LLMs generate relevant entity pairs grounded by retrieval corpora as valid queries. These entity pairs are then used to retrieve relevant training examples from the retrieval corpora as demonstrations for LLMs to conduct better ICL via instruction tuning. Extensive experiments on different LLMs and RE datasets demonstrate that our method generates relevant and valid entity pairs and boosts ICL abilities of LLMs achieving competitive or new state45;of45;the45;art performance on sentence45;level RE compared to previous supervised fine45;tuning methods and ICL45;based methods.
