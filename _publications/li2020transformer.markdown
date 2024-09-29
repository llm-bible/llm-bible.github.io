---
layout: publication
title: Transformer-based Neural Text Generation With Syntactic Guidance
authors: Li Yinghao Georgia Institute Of Technology, Feng Rui Georgia Institute Of Technology, Rehg Isaac Georgia Institute Of Technology, Zhang Chao Georgia Institute Of Technology
conference: "Arxiv"
year: 2020
bibkey: li2020transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.01737"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
We study the problem of using (partial) constituency parse trees as syntactic guidance for controlled text generation. Existing approaches to this problem use recurrent structures which not only suffer from the long-term dependency problem but also falls short in modeling the tree structure of the syntactic guidance. We propose to leverage the parallelism of Transformer to better incorporate parse trees. Our method first expands a partial template constituency parse tree to a full-fledged parse tree tailored for the input source text and then uses the expanded tree to guide text generation. The effectiveness of our model in this process hinges upon two new attention mechanisms 1) a path attention mechanism that forces one node to attend to only other nodes located in its path in the syntax tree to better incorporate syntax guidance; 2) a multi-encoder attention mechanism that allows the decoder to dynamically attend to information from multiple encoders. Our experiments in the controlled paraphrasing task show that our method outperforms SOTA models both semantically and syntactically improving the best baselines BLEU score from 11.83 to 26.27.
