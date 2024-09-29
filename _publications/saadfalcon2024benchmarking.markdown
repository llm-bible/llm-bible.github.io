---
layout: publication
title: Benchmarking And Building Long45;context Retrieval Models With Loco And M245;BERT
authors: Saad-falcon Jon, Fu Daniel Y., Arora Simran, Guha Neel, Ré Christopher
conference: "Arxiv"
year: 2024
bibkey: saadfalcon2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07440"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Retrieval pipelines45;an integral component of many machine learning systems45;perform poorly in domains where documents are long (e.g. 10K tokens or more) and where identifying the relevant document requires synthesizing information across the entire text. Developing long45;context retrieval encoders suitable for these domains raises three challenges (1) how to evaluate long45;context retrieval performance (2) how to pretrain a base language model to represent both short contexts (corresponding to queries) and long contexts (corresponding to documents) and (3) how to fine45;tune this model for retrieval under the batch size limitations imposed by GPU memory constraints. To address these challenges we first introduce LoCoV1 a novel 12 task benchmark constructed to measure long45;context retrieval where chunking is not possible or not effective. We next present the M245;BERT retrieval encoder an 80M parameter state45;space encoder model built from the Monarch Mixer architecture capable of scaling to documents up to 32K tokens long. We describe a pretraining data mixture which allows this encoder to process both short and long context sequences and a finetuning approach that adapts this base model to retrieval with only single45;sample batches. Finally we validate the M245;BERT retrieval encoder on LoCoV1 finding that it outperforms competitive Transformer45;based models by at least 23.3 points despite containing upwards of 90x fewer parameters.
