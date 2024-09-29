---
layout: publication
title: Code Generation From Natural Language With Less Prior And More Monolingual Data
authors: Norouzi Sajad, Tang Keyi, Cao Yanshuai
conference: "Arxiv"
year: 2021
bibkey: norouzi2021code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.00259"}
tags: ['Applications', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Training datasets for semantic parsing are typically small due to the higher expertise required for annotation than most other NLP tasks. As a result models for this application usually need additional prior knowledge to be built into the architecture or algorithm. The increased dependency on human experts hinders automation and raises the development and maintenance costs in practice. This work investigates whether a generic transformer-based seq2seq model can achieve competitive performance with minimal code-generation-specific inductive bias design. By exploiting a relatively sizeable monolingual corpus of the target programming language which is cheap to mine from the web we achieved 81.0337; exact match accuracy on Django and 32.57 BLEU score on CoNaLa. Both are SOTA to the best of our knowledge. This positive evidence highlights a potentially easier path toward building accurate semantic parsers in practice.
