---
layout: publication
title: SPARSEFIT Few45;shot Prompting With Sparse Fine45;tuning For Jointly Generating Predictions And Natural Language Explanations
authors: Solano Jesus, Sanni Mardhiyah, Camburu Oana-maria, Minervini Pasquale
conference: "ACL"
year: 2023
bibkey: solano2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13235"}
tags: ['Applications', 'Interpretability And Explainability', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Models that generate natural language explanations (NLEs) for their predictions have recently gained increasing interest. However this approach usually demands large datasets of human45;written NLEs for the ground45;truth answers at training time which can be expensive and potentially infeasible for some applications. When only a few NLEs are available (a few45;shot setup) fine45;tuning pre45;trained language models (PLMs) in conjunction with prompt45;based learning has recently shown promising results. However PLMs typically have billions of parameters making full fine45;tuning expensive. We propose SparseFit a sparse few45;shot fine45;tuning strategy that leverages discrete prompts to jointly generate predictions and NLEs. We experiment with SparseFit on three sizes of the T5 language model and four datasets and compare it against existing state45;of45;the45;art Parameter45;Efficient Fine45;Tuning (PEFT) techniques. We find that fine45;tuning only 6.837; of the model parameters leads to competitive results for both the task performance and the quality of the generated NLEs compared to full fine45;tuning of the model and produces better results on average than other PEFT methods in terms of predictive accuracy and NLE quality.
