---
layout: publication
title: 'Kb-plugin: A Plug-and-play Framework For Large Language Models To Induce Programs Over Low-resourced Knowledge Bases'
authors: Zhang Jiajie, Cao Shulin, Hu Linmei, Feng Ling, Hou Lei, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: zhang2024kb
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01619"}
  - {name: "Code", url: "https://github.com/THU-KEG/KB-Plugin"}
tags: ['Has Code', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Program induction (PI) has become a promising paradigm for using knowledge bases (KBs) to help large language models (LLMs) answer complex knowledge-intensive questions. Nonetheless, PI typically relies on a large number of parallel question-program pairs to make the LLM aware of the schema of the given KB, and is thus challenging for many low-resourced KBs that lack annotated data. To this end, we propose KB-Plugin, a plug-and-play framework that enables LLMs to induce programs over any low-resourced KB. Firstly, KB-Plugin adopts self-supervised learning to encode the detailed schema information of a given KB into a pluggable module, namely schema plugin. Secondly, KB-Plugin utilizes abundant annotated data from a rich-resourced KB to train another pluggable module, namely PI plugin, which can help the LLM extract question-relevant schema information from the schema plugin of any KB and utilize this information to induce programs over this KB. Experiments on five heterogeneous KBQA datasets show that KB-Plugin achieves better or comparable performance with 25\\(\times\\) smaller backbone LLM compared to SoTA PI methods for low-resourced KBs, and even approaches the performance of supervised methods. Our code and data are available at https://github.com/THU-KEG/KB-Plugin.
