---
layout: publication
title: Towards Fine45;tuning Pre45;trained Language Models With Integer Forward And Backward Propagation
authors: Tayaranian Mohammadreza, Ghaffari Alireza, Tahaei Marzieh S., Rezagholizadeh Mehdi, Asgharian Masoud, Nia Vahid Partovi
conference: "Arxiv"
year: 2022
bibkey: tayaranian2022towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.09815"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
The large number of parameters of some prominent language models such as BERT makes their fine45;tuning on downstream tasks computationally intensive and energy hungry. Previously researchers were focused on lower bit45;width integer data types for the forward propagation of language models to save memory and computation. As for the backward propagation however only 1645;bit floating45;point data type has been used for the fine45;tuning of BERT. In this work we use integer arithmetic for both forward and back propagation in the fine45;tuning of BERT. We study the effects of varying the integer bit45;width on the models metric performance. Our integer fine45;tuning uses integer arithmetic to perform forward propagation and gradient computation of linear layer45;norm and embedding layers of BERT. We fine45;tune BERT using our integer training method on SQuAD v1.1 and SQuAD v2. and GLUE benchmark. We demonstrate that metric performance of fine45;tuning 1645;bit integer BERT matches both 1645;bit and 3245;bit floating45;point baselines. Furthermore using the faster and more memory efficient 845;bit integer data type integer fine45;tuning of BERT loses an average of 3.1 points compared to the FP32 baseline.
