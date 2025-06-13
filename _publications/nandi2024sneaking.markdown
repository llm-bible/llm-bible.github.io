---
layout: publication
title: 'Sneaking Syntax Into Transformer Language Models With Tree Regularization'
authors: Ananjan Nandi, Christopher D. Manning, Shikhar Murty
conference: "Arxiv"
year: 2024
bibkey: nandi2024sneaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18885"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Ethics and Bias', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods']
---
While compositional accounts of human language understanding are based on a
hierarchical tree-like process, neural models like transformers lack a direct
inductive bias for such tree structures. Introducing syntactic inductive biases
could unlock more robust and data-efficient learning in transformer language
models (LMs), but existing methods for incorporating such structure greatly
restrict models, either limiting their expressivity or increasing inference
complexity. This work instead aims to softly inject syntactic inductive biases
into given transformer circuits, through a structured regularizer. We introduce
TreeReg, an auxiliary loss function that converts bracketing decisions from
silver parses into a set of differentiable orthogonality constraints on vector
hidden states. TreeReg integrates seamlessly with the standard LM objective,
requiring no architectural changes. LMs pre-trained with TreeReg on natural
language corpora such as WikiText-103 achieve up to 10% lower perplexities on
out-of-distribution data and up to 9.5 point improvements in syntactic
generalization, requiring less than half the training data to outperform
standard LMs. TreeReg still provides gains for pre-trained LLMs: Continued
pre-training of Sheared Llama with TreeReg results in improved syntactic
generalization, and fine-tuning on MultiNLI with TreeReg mitigates degradation
of performance on adversarial NLI benchmarks by 41.2 points. We release all
code to guide future research.
