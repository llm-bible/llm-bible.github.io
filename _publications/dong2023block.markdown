---
layout: publication
title: Block45;wise Bit45;compression Of Transformer45;based Models
authors: Dong Gaochen, Chen Wei
conference: "Arxiv"
year: 2023
bibkey: dong2023block
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.09184"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
With the popularity of the recent Transformer45;based models represented by BERT GPT45;3 and ChatGPT there has been state45;of45;the45;art performance in a range of natural language processing tasks. However the massive computations huge memory footprint and thus high latency of Transformer45;based models is an inevitable challenge for the cloud with high real45;time requirement. To tackle the issue we propose BBCT a method of block45;wise bit45;compression for transformer without retraining. Our method achieves more fine45;grained compression of the whole transformer including embedding matrix multiplication GELU softmax layer normalization and all the intermediate results. As a case we compress an efficient BERT with the method of BBCT. Our benchmark test results on General Language Understanding Evaluation (GLUE) show that BBCT can achieve less than 137; accuracy drop in most tasks.
