---
layout: publication
title: SPARSEFIT: Few-shot Prompting With Sparse Fine-tuning For Jointly Generating Predictions And Natural Language Explanations
authors: Solano Jesus, Sanni Mardhiyah, Camburu Oana-maria, Minervini Pasquale
conference: "ACL"
year: 2023
bibkey: solano2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13235"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'In Context Learning', 'Interpretability And Explainability', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Models that generate natural language explanations (NLEs) for their predictions have recently gained increasing interest. However this approach usually demands large datasets of human-written NLEs for the ground-truth answers at training time which can be expensive and potentially infeasible for some applications. When only a few NLEs are available (a few-shot setup) fine-tuning pre-trained language models (PLMs) in conjunction with prompt-based learning has recently shown promising results. However PLMs typically have billions of parameters making full fine-tuning expensive. We propose SparseFit a sparse few-shot fine-tuning strategy that leverages discrete prompts to jointly generate predictions and NLEs. We experiment with SparseFit on three sizes of the T5 language model and four datasets and compare it against existing state-of-the-art Parameter-Efficient Fine-Tuning (PEFT) techniques. We find that fine-tuning only 6.837; of the model parameters leads to competitive results for both the task performance and the quality of the generated NLEs compared to full fine-tuning of the model and produces better results on average than other PEFT methods in terms of predictive accuracy and NLE quality.
