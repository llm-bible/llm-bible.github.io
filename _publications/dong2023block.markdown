---
layout: publication
title: 'Block-wise Bit-compression Of Transformer-based Models'
authors: Gaochen Dong, Wei Chen
conference: "Arxiv"
year: 2023
bibkey: dong2023block
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.09184"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
With the popularity of the recent Transformer-based models represented by
BERT, GPT-3 and ChatGPT, there has been state-of-the-art performance in a range
of natural language processing tasks. However, the massive computations, huge
memory footprint, and thus high latency of Transformer-based models is an
inevitable challenge for the cloud with high real-time requirement. To tackle
the issue, we propose BBCT, a method of block-wise bit-compression for
transformer without retraining. Our method achieves more fine-grained
compression of the whole transformer, including embedding, matrix
multiplication, GELU, softmax, layer normalization, and all the intermediate
results. As a case, we compress an efficient BERT with the method of BBCT. Our
benchmark test results on General Language Understanding Evaluation (GLUE) show
that BBCT can achieve less than 1% accuracy drop in most tasks.
