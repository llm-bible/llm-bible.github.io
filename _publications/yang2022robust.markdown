---
layout: publication
title: 'Tableformer: Robust Transformer Modeling For Table-text Encoding'
authors: Jingfeng Yang, Aditya Gupta, Shyam Upadhyay, Luheng He, Rahul Goel, Shachi Paul
conference: "Arxiv"
year: 2022
bibkey: yang2022robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.00274"}
tags: ['Model Architecture', 'Pretraining Methods', 'Ethics and Bias', 'Transformer', 'Attention Mechanism']
---
Understanding tables is an important aspect of natural language
understanding. Existing models for table understanding require linearization of
the table structure, where row or column order is encoded as an unwanted bias.
Such spurious biases make the model vulnerable to row and column order
perturbations. Additionally, prior work has not thoroughly modeled the table
structures or table-text alignments, hindering the table-text understanding
ability. In this work, we propose a robust and structurally aware table-text
encoding architecture TableFormer, where tabular structural biases are
incorporated completely through learnable attention biases. TableFormer is (1)
strictly invariant to row and column orders, and, (2) could understand tables
better due to its tabular inductive biases. Our evaluations showed that
TableFormer outperforms strong baselines in all settings on SQA, WTQ and
TabFact table reasoning datasets, and achieves state-of-the-art performance on
SQA, especially when facing answer-invariant row and column order perturbations
(6% improvement over the best baseline), because previous SOTA models'
performance drops by 4% - 6% when facing such perturbations while TableFormer
is not affected.
