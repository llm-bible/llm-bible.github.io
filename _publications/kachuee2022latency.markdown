---
layout: publication
title: 'Latency Adjustable Transformer Encoder For Language Understanding'
authors: Kachuee Sajjad, Sharifkhani Mohammad
conference: "Arxiv"
year: 2022
bibkey: kachuee2022latency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.03327"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Adjusting the latency, power, and accuracy of natural language understanding models is a desirable objective of an efficient architecture. This paper proposes an efficient Transformer architecture that adjusts the inference computational cost adaptively with a desired inference latency speedup. In fine-tuning phase, the proposed method detects less important hidden sequence elements (word-vectors) and eliminates them in each encoder layer using a proposed Attention Context Contribution (ACC) metric. After the fine-tuning phase, with the novel offline-tuning property, the inference latency of the model can be adjusted in a wide range of inference speedup selections without any further training. The proposed method is applied to the BERT\_base, GPT-2 and Flan-T5 models for evaluation. Extensive experiments show that most of the word-vectors in higher Transformer layers have less contribution to the subsequent layers; hence, they can be eliminated to improve the inference latency. Experimental results on extensive sentiment analysis, classification, text generation tasks and regression benchmarks like GLUE showed that the method is effective in various datasets with minimal impact on the input's global context. The method was also evaluated under the instruction tuning paradigm, and its performance was measured using different types of prompting. The proposed method mathematically and experimentally improves the inference latency of BERT\_base and GPT-2 by up to 4.8 and 3.72 times with less than 0.75&#37; accuracy drop and passable perplexity on average. The suggested approach posits that in Large Language Models (LLMs), although the complete network is necessary for training, it can be truncated during the fine-tuning phase.
