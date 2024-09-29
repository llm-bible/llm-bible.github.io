---
layout: publication
title: Generate Annotate And Learn NLP With Synthetic Text
authors: He Xuanli, Nassar Islam, Kiros Jamie, Haffari Gholamreza, Norouzi Mohammad
conference: "Arxiv"
year: 2021
bibkey: he2021nlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.06168"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
This paper studies the use of language models as a source of synthetic unlabeled text for NLP. We formulate a general framework called generate annotate and learn (GAL) to take advantage of synthetic text within knowledge distillation self45;training and few45;shot learning applications. To generate high45;quality task45;specific text we either fine45;tune LMs on inputs from the task of interest or prompt large LMs with few examples. We use the best available classifier to annotate synthetic text with soft pseudo labels for knowledge distillation and self45;training and use LMs to obtain hard labels for few45;shot learning. We train new supervised models on the combination of labeled and pseudo45;labeled data which results in significant gains across several applications. We investigate key components of GAL and present theoretical and empirical arguments against the use of class45;conditional LMs to generate synthetic labeled text instead of unlabeled text. GAL achieves new state45;of45;the45;art knowledge distillation results for 645;layer transformers on the GLUE leaderboard.
