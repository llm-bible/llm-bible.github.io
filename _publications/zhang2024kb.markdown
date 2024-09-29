---
layout: publication
title: Kb45;plugin A Plug45;and45;play Framework For Large Language Models To Induce Programs Over Low45;resourced Knowledge Bases
authors: Zhang Jiajie, Cao Shulin, Hu Linmei, Feng Ling, Hou Lei, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: zhang2024kb
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01619"}
  - {name: "Code", url: "https://github.com/THU&#45;KEG/KB&#45;Plugin"}
tags: ['Has Code', 'Pretraining Methods', 'Tools']
---
Program induction (PI) has become a promising paradigm for using knowledge bases (KBs) to help large language models (LLMs) answer complex knowledge45;intensive questions. Nonetheless PI typically relies on a large number of parallel question45;program pairs to make the LLM aware of the schema of the given KB and is thus challenging for many low45;resourced KBs that lack annotated data. To this end we propose KB45;Plugin a plug45;and45;play framework that enables LLMs to induce programs over any low45;resourced KB. Firstly KB45;Plugin adopts self45;supervised learning to encode the detailed schema information of a given KB into a pluggable module namely schema plugin. Secondly KB45;Plugin utilizes abundant annotated data from a rich45;resourced KB to train another pluggable module namely PI plugin which can help the LLM extract question45;relevant schema information from the schema plugin of any KB and utilize this information to induce programs over this KB. Experiments on five heterogeneous KBQA datasets show that KB45;Plugin achieves better or comparable performance with 25× smaller backbone LLM compared to SoTA PI methods for low45;resourced KBs and even approaches the performance of supervised methods. Our code and data are available at https://github.com/THU&#45;KEG/KB&#45;Plugin.
