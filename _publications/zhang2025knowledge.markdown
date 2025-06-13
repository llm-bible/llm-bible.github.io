---
layout: publication
title: 'Inhibidistilbert: Knowledge Distillation For A Relu And Addition-based Transformer'
authors: Tony Zhang, Rickard Brännvall
conference: "Arxiv"
year: 2025
bibkey: zhang2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15983"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'Quantization', 'Pretraining Methods', 'BERT', 'Transformer', 'Attention Mechanism']
---
This work explores optimizing transformer-based language models by
integrating model compression techniques with inhibitor attention, a novel
alternative attention mechanism. Inhibitor attention employs Manhattan
distances and ReLU activations instead of the matrix multiplications and
softmax activation of the conventional scaled dot-product attention. This shift
offers potential computational and energy savings while maintaining model
effectiveness. We propose further adjustments to improve the inhibitor
mechanism's training efficiency and evaluate its performance on the DistilBERT
architecture. Our knowledge distillation experiments indicate that the modified
inhibitor transformer model can achieve competitive performance on standard NLP
benchmarks, including General Language Understanding Evaluation (GLUE) and
sentiment analysis tasks.
