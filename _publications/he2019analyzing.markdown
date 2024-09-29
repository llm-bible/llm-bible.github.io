---
layout: publication
title: Analyzing The Forgetting Problem In The Pretrain45;finetuning Of Dialogue Response Models
authors: He Tianxing, Liu Jun, Cho Kyunghyun, Ott Myle, Liu Bing, Glass James, Peng Fuchun
conference: "EACL"
year: 2019
bibkey: he2019analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.07117"}
tags: ['Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Tools', 'Training Techniques', 'Transformer']
---
In this work we study how the finetuning stage in the pretrain45;finetune framework changes the behavior of a pretrained neural language generator. We focus on the transformer encoder45;decoder model for the open45;domain dialogue response generation task. Our major finding is that after standard finetuning the model forgets some of the important language generation skills acquired during large45;scale pretraining. We demonstrate the forgetting phenomenon through a set of detailed behavior analysis from the perspectives of knowledge transfer context sensitivity and function space projection. As a preliminary attempt to alleviate the forgetting problem we propose an intuitive finetuning strategy named mix45;review. We find that mix45;review effectively regularizes the finetuning process and the forgetting problem is alleviated to some extent. Finally we discuss interesting behavior of the resulting dialogue model and its implications.
