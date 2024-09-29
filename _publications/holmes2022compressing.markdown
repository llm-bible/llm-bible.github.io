---
layout: publication
title: Compressing Pre45;trained Transformers Via Low45;bit Nxm Sparsity For Natural Language Understanding
authors: Holmes Connor, Zhang Minjia, He Yuxiong, Wu Bo
conference: "Arxiv"
year: 2022
bibkey: holmes2022compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.15014"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Tools', 'Transformer']
---
In recent years large pre45;trained Transformer networks have demonstrated dramatic improvements in many natural language understanding tasks. However the huge size of these models brings significant challenges to their fine45;tuning and online deployment due to latency and cost constraints. New hardware supporting both NM semi45;structured sparsity and low45;precision integer computation is a promising solution to boost DNN model serving efficiency. However there have been very few studies that systematically investigate to what extent pre45;trained Transformer networks benefit from the combination of these techniques as well as how to best compress each component of the Transformer. We propose a flexible compression framework NxMiFormer that performs simultaneous sparsification and quantization using ADMM and STE45;based QAT. Furthermore we present and inexpensive heuristic45;driven search algorithm that identifies promising heterogeneous compression configurations that meet a compression ratio constraint. When evaluated across the GLUE suite of NLU benchmarks our approach can achieve up to 9337; compression of the encoders of a BERT model while retaining 98.237; of the original model accuracy and taking full advantage of the hardwares capabilities. Heterogeneous configurations found the by the search heuristic maintain 99.537; of the baseline accuracy while still compressing the model by 87.537;.
