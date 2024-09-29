---
layout: publication
title: Lightseq A High Performance Inference Library For Transformers
authors: Wang Xiaohui, Xiong Ying, Wei Yang, Wang Mingxuan, Li Lei
conference: "Arxiv"
year: 2020
bibkey: wang2020high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.13887"}
  - {name: "Code", url: "https://github.com/bytedance/lightseq"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Transformer BERT and their variants have achieved great success in natural language processing. Since Transformer models are huge in size serving these models is a challenge for real industrial applications. In this paper we propose LightSeq a highly efficient inference library for models in the Transformer family. LightSeq includes a series of GPU optimization techniques to to streamline the computation of neural layers and to reduce memory footprint. LightSeq can easily import models trained using PyTorch and Tensorflow. Experimental results on machine translation benchmarks show that LightSeq achieves up to 14x speedup compared with TensorFlow and 1.4x compared with FasterTransformer a concurrent CUDA implementation. The code is available at https://github.com/bytedance/lightseq.
