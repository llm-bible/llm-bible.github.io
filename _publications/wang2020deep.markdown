---
layout: publication
title: Minilm Deep Self45;attention Distillation For Task45;agnostic Compression Of Pre45;trained Transformers
authors: Wang Wenhui, Wei Furu, Dong Li, Bao Hangbo, Yang Nan, Zhou Ming
conference: "Arxiv"
year: 2020
bibkey: wang2020deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.10957"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Pre45;trained language models (e.g. BERT (Devlin et al. 2018) and its variants) have achieved remarkable success in varieties of NLP tasks. However these models usually consist of hundreds of millions of parameters which brings challenges for fine45;tuning and online serving in real45;life applications due to latency and capacity constraints. In this work we present a simple and effective approach to compress large Transformer (Vaswani et al. 2017) based pre45;trained models termed as deep self45;attention distillation. The small model (student) is trained by deeply mimicking the self45;attention module which plays a vital role in Transformer networks of the large model (teacher). Specifically we propose distilling the self45;attention module of the last Transformer layer of the teacher which is effective and flexible for the student. Furthermore we introduce the scaled dot45;product between values in the self45;attention module as the new deep self45;attention knowledge in addition to the attention distributions (i.e. the scaled dot45;product of queries and keys) that have been used in existing works. Moreover we show that introducing a teacher assistant (Mirzadeh et al. 2019) also helps the distillation of large pre45;trained Transformer models. Experimental results demonstrate that our monolingual model outperforms state45;of45;the45;art baselines in different parameter size of student models. In particular it retains more than 9937; accuracy on SQuAD 2.0 and several GLUE benchmark tasks using 5037; of the Transformer parameters and computations of the teacher model. We also obtain competitive results in applying deep self45;attention distillation to multilingual pre45;trained models.
