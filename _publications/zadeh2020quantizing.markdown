---
layout: publication
title: GOBO Quantizing Attention45;based NLP Models For Low Latency And Energy Efficient Inference
authors: Zadeh Ali Hadi, Edo Isak, Awad Omar Mohamed, Moshovos Andreas
conference: "Arxiv"
year: 2020
bibkey: zadeh2020quantizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.03842"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Quantization', 'RAG', 'Training Techniques']
---
Attention45;based models have demonstrated remarkable success in various natural language understanding tasks. However efficient execution remains a challenge for these models which are memory45;bound due to their massive number of parameters. We present GOBO a model quantization technique that compresses the vast majority (typically 99.937;) of the 3245;bit floating45;point parameters of state45;of45;the45;art BERT models and their variants to 3 bits while maintaining their accuracy. Unlike other quantization methods GOBO does not require fine45;tuning nor retraining to compensate for the quantization error. We present two practical hardware applications of GOBO. In the first GOBO reduces memory storage and traffic and as a result inference latency and energy consumption. This GOBO memory compression mechanism is plug45;in compatible with many architectures; we demonstrate it with the TPU Eyeriss and an architecture using Tensor Cores45;like units. Second we present a co45;designed hardware architecture that also reduces computation. Uniquely the GOBO architecture maintains most of the weights in 3b even during computation a property that (1) makes the processing elements area efficient allowing us to pack more compute power per unit area (2) replaces most multiply45;accumulations with additions and (3) reduces the off45;chip traffic by amplifying on45;chip memory capacity.
