---
layout: publication
title: 'Sorted Llama: Unlocking The Potential Of Intermediate Layers Of Large Language Models For Dynamic Inference'
authors: Parsa Kavehzadeh, Mojtaba Valipour, Marzieh Tahaei, Ali Ghodsi, Boxing Chen, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2023
bibkey: kavehzadeh2023sorted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08968"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have revolutionized natural language processing
(NLP) by excelling at understanding and generating human-like text. However,
their widespread deployment can be prohibitively expensive. SortedNet is a
recent training technique for enabling dynamic inference by leveraging the
modularity in networks and sorting sub-models based on computation/accuracy in
a nested manner. We extend SortedNet to generative NLP tasks, making large
language models dynamic without any Pre-Training and by only replacing Standard
Fine-Tuning (SFT) with Sorted Fine-Tuning (SoFT). Our approach boosts model
efficiency, eliminating the need for multiple models for various scenarios
during inference. We show that this approach can unlock the power of
intermediate layers of transformers in generating the target output. Our
sub-models remain integral components of the original model, minimizing storage
requirements and transition costs between different computational/latency
budgets. The efficacy of our proposed method was demonstrated by applying it to
tune LLaMA 2 13B on the Stanford Alpaca dataset for instruction following and
TriviaQA for closed-book question answering. Our results show the superior
performance of sub-models in comparison to Standard Fine-Tuning and SFT+ICT
(Early-Exit), all achieved with efficient tuning and without additional memory
usage during inference.
