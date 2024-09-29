---
layout: publication
title: 'Towards Fine-tuning Pre-trained Language Models With Integer Forward And Backward Propagation'
authors: Tayaranian Mohammadreza, Ghaffari Alireza, Tahaei Marzieh S., Rezagholizadeh Mehdi, Asgharian Masoud, Nia Vahid Partovi
conference: "Arxiv"
year: 2022
bibkey: tayaranian2022towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.09815"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
The large number of parameters of some prominent language models such as BERT makes their fine-tuning on downstream tasks computationally intensive and energy hungry. Previously researchers were focused on lower bit-width integer data types for the forward propagation of language models to save memory and computation. As for the backward propagation however only 16-bit floating-point data type has been used for the fine-tuning of BERT. In this work we use integer arithmetic for both forward and back propagation in the fine-tuning of BERT. We study the effects of varying the integer bit-width on the models metric performance. Our integer fine-tuning uses integer arithmetic to perform forward propagation and gradient computation of linear layer-norm and embedding layers of BERT. We fine-tune BERT using our integer training method on SQuAD v1.1 and SQuAD v2. and GLUE benchmark. We demonstrate that metric performance of fine-tuning 16-bit integer BERT matches both 16-bit and 32-bit floating-point baselines. Furthermore using the faster and more memory efficient 8-bit integer data type integer fine-tuning of BERT loses an average of 3.1 points compared to the FP32 baseline.
