---
layout: publication
title: Budgetlongformer Can We Cheaply Pretrain A Sota Legal Language Model From Scratch
authors: Niklaus Joel, Giofré Daniele
conference: "Arxiv"
year: 2022
bibkey: niklaus2022can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.17135"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Pretrained transformer models have achieved state45;of45;the45;art results in many tasks and benchmarks recently. Many state45;of45;the45;art Language Models (LMs) however do not scale well above the threshold of 512 input tokens. In specialized domains though (such as legal scientific or biomedical) models often need to process very long text (sometimes well above 10000 tokens). Even though many efficient transformers have been proposed (such as Longformer BigBird or FNet) so far only very few such efficient models are available for specialized domains. Additionally since the pretraining process is extremely costly in general 45; but even more so as the sequence length increases 45; it is often only in reach of large research labs. One way of making pretraining cheaper is the Replaced Token Detection (RTD) task by providing more signal during training since the loss can be computed over all tokens. In this work we train Longformer models with the efficient RTD task on legal data to showcase that pretraining efficient LMs is possible using much less compute. We evaluate the trained models on challenging summarization tasks requiring the model to summarize long texts to show to what extent the models can achieve good performance on downstream tasks. We find that both the small and base models outperform their baselines on the in45;domain BillSum and out45;of45;domain PubMed tasks in their respective parameter range. We publish our code and models for research purposes.
