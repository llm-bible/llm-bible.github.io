---
layout: publication
title: Cross45;lingual Machine Reading Comprehension
authors: Cui Yiming, Che Wanxiang, Liu Ting, Qin Bing, Wang Shijin, Hu Guoping
conference: "EMNLP"
year: 2019
bibkey: cui2019cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.00361"}
  - {name: "Code", url: "https://github.com/ymcui/Cross&#45;Lingual&#45;MRC"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Training Techniques']
---
Though the community has made great progress on Machine Reading Comprehension (MRC) task most of the previous works are solving English45;based MRC problems and there are few efforts on other languages mainly due to the lack of large45;scale training data. In this paper we propose Cross45;Lingual Machine Reading Comprehension (CLMRC) task for the languages other than English. Firstly we present several back45;translation approaches for CLMRC task which is straightforward to adopt. However to accurately align the answer into another language is difficult and could introduce additional noise. In this context we propose a novel model called Dual BERT which takes advantage of the large45;scale training data provided by rich45;resource language (such as English) and learn the semantic relations between the passage and question in a bilingual context and then utilize the learned knowledge to improve reading comprehension performance of low45;resource language. We conduct experiments on two Chinese machine reading comprehension datasets CMRC 2018 and DRCD. The results show consistent and significant improvements over various state45;of45;the45;art systems by a large margin which demonstrate the potentials in CLMRC task. Resources available https://github.com/ymcui/Cross&#45;Lingual&#45;MRC
