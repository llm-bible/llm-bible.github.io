---
layout: publication
title: Using Deepspeed And Megatron To Train Megatron45;turing NLG 530B A Large45;scale Generative Language Model
authors: Shaden Smith, Mostofa Patwary, Brandon Norick, Patrick Legresley, Samyam Rajbhandari, Jared Casper, Zhun Liu, Shrimai Prabhumoye, George Zerveas, Vijay Korthikanti, Elton Zhang, Rewon Child, Reza Yazdani Aminabadi, Julie Bernauer, Xia Song, Mohammad Shoeybi, Yuxiong He, Michael Houston, Saurabh Tiwary, Bryan Catanzaro
conference: "Arxiv"
year: 2022
bibkey: smith2022using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2201.11990v3"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Pretrained general45;purpose language models can achieve state45;of45;the45;art accuracies in various natural language processing domains by adapting to downstream tasks via zero45;shot few45;shot and fine45;tuning techniques. Because of their success the size of these models has increased rapidly requiring high45;performance hardware software and algorithmic techniques to enable training such large models. As the result of a joint effort between Microsoft and NVIDIA we present details on the training of the largest monolithic transformer based language model Megatron45;Turing NLG 530B (MT45;NLG) with 530 billion parameters. In this paper we first focus on the infrastructure as well as the 3D parallelism methodology used to train this model using DeepSpeed and Megatron. Next we detail the training process the design of our training corpus and our data curation techniques which we believe is a key ingredient to the success of the model. Finally we discuss various evaluation results as well as other interesting observations and new properties exhibited by MT45;NLG. We demonstrate that MT45;NLG achieves superior zero45; one45; and few45;shot learning accuracies on several NLP benchmarks and establishes new state45;of45;the45;art results. We believe that our contributions will help further the development of large45;scale training infrastructures large45;scale language models and natural language generations.
