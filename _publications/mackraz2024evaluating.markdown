---
layout: publication
title: 'Evaluating Gender Bias Transfer Between Pre-trained And Prompt-adapted Language Models'
authors: Natalie Mackraz, Nivedha Sivakumar, Samira Khorshidi, Krishna Patel, Barry-john Theobald, Luca Zappella, Nicholas Apostoloff
conference: "Arxiv"
year: 2024
bibkey: mackraz2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03537"}
tags: ['Masked Language Model', 'Training Techniques', 'Fairness', 'Few-Shot', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) are increasingly being adapted to achieve
task-specificity for deployment in real-world decision systems. Several
previous works have investigated the bias transfer hypothesis (BTH) by studying
the effect of the fine-tuning adaptation strategy on model fairness to find
that fairness in pre-trained masked language models have limited effect on the
fairness of models when adapted using fine-tuning. In this work, we expand the
study of BTH to causal models under prompt adaptations, as prompting is an
accessible, and compute-efficient way to deploy models in real-world systems.
In contrast to previous works, we establish that intrinsic biases in
pre-trained Mistral, Falcon and Llama models are strongly correlated (rho >=
0.94) with biases when the same models are zero- and few-shot prompted, using a
pronoun co-reference resolution task. Further, we find that bias transfer
remains strongly correlated even when LLMs are specifically prompted to exhibit
fair or biased behavior (rho >= 0.92), and few-shot length and stereotypical
composition are varied (rho >= 0.97). Our findings highlight the importance of
ensuring fairness in pre-trained LLMs, especially when they are later used to
perform downstream tasks via prompt adaptation.
