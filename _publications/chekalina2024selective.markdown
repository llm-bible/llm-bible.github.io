---
layout: publication
title: 'Sparsegrad: A Selective Method For Efficient Fine-tuning Of MLP Layers'
authors: Viktoriia Chekalina, Anna Rudenko, Gleb Mezentsev, Alexander Mikhalev, Alexander Panchenko, Ivan Oseledets
conference: "Arxiv"
year: 2024
bibkey: chekalina2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07383"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning', 'Attention Mechanism']
---
The performance of Transformer models has been enhanced by increasing the
number of parameters and the length of the processed text. Consequently,
fine-tuning the entire model becomes a memory-intensive process.
High-performance methods for parameter-efficient fine-tuning (PEFT) typically
work with Attention blocks and often overlook MLP blocks, which contain about
half of the model parameters. We propose a new selective PEFT method, namely
SparseGrad, that performs well on MLP blocks. We transfer layer gradients to a
space where only about 1% of the layer's elements remain significant. By
converting gradients into a sparse structure, we reduce the number of updated
parameters. We apply SparseGrad to fine-tune BERT and RoBERTa for the NLU task
and LLaMa-2 for the Question-Answering task. In these experiments, with
identical memory requirements, our method outperforms LoRA and MeProp, robust
popular state-of-the-art PEFT approaches.
