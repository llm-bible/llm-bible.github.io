---
layout: publication
title: 'Lola: Low-rank Linear Attention With Sparse Caching'
authors: Luke Mcdermott, Robert W. Jr. Heath, Rahul Parhi
conference: "Arxiv"
year: 2025
bibkey: mcdermott2025low
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23666'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based large language models suffer from quadratic complexity at inference on long sequences. Linear attention methods are efficient alternatives, however, they fail to provide an accurate approximation of softmax attention. By additionally incorporating sliding window attention into each linear attention head, this gap can be closed for short context-length tasks. Unfortunately, these approaches cannot recall important information from long contexts due to "memory collisions". In this paper , we propose LoLA: Low-rank Linear Attention with sparse caching. LoLA separately stores additional key-value pairs that would otherwise interfere with past associative memories. Moreover, LoLA further closes the gap between linear attention models and transformers by distributing past key-value pairs into three forms of memory: (i) recent pairs in a local sliding window; (ii) difficult-to-memorize pairs in a sparse, global cache; and (iii) generic pairs in the recurrent hidden state of linear attention. As an inference-only strategy, LoLA enables pass-key retrieval on up to 8K context lengths on needle-in-a-haystack tasks from RULER. It boosts the accuracy of the base subquadratic model from 0.6% to 97.4% at 4K context lengths, with a 4.6x smaller cache than that of Llama-3.1 8B. LoLA demonstrates strong performance on zero-shot commonsense reasoning tasks among 1B and 8B parameter subquadratic models. Finally, LoLA is an extremely lightweight approach: Nearly all of our results can be reproduced on a single consumer GPU.
