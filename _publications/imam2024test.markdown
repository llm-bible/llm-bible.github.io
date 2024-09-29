---
layout: publication
title: Test45;time Low Rank Adaptation Via Confidence Maximization For Zero45;shot Generalization Of Vision45;language Models
authors: Imam Raza, Gani Hanan, Huzaifa Muhammad, Nandakumar Karthik
conference: "Arxiv"
year: 2024
bibkey: imam2024test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15913"}
  - {name: "Code", url: "https://github.com/Razaimam45/TTL&#45;Test&#45;Time&#45;Low&#45;Rank&#45;Adaptation"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
The conventional modus operandi for adapting pre45;trained vision45;language models (VLMs) during test45;time involves tuning learnable prompts ie test45;time prompt tuning. This paper introduces Test45;Time Low45;rank adaptation (TTL) as an alternative to prompt tuning for zero45;shot generalization of large45;scale VLMs. Taking inspiration from recent advancements in efficiently fine45;tuning large language models TTL offers a test45;time parameter45;efficient adaptation approach that updates the attention weights of the transformer encoder by maximizing prediction confidence. The self45;supervised confidence maximization objective is specified using a weighted entropy loss that enforces consistency among predictions of augmented samples. TTL introduces only a small amount of trainable parameters for low45;rank adapters in the model space while keeping the prompts and backbone frozen. Extensive experiments on a variety of natural distribution and cross45;domain tasks show that TTL can outperform other techniques for test45;time optimization of VLMs in strict zero45;shot settings. Specifically TTL outperforms test45;time prompt tuning baselines with a significant improvement on average. Our code is available at at https://github.com/Razaimam45/TTL&#45;Test&#45;Time&#45;Low&#45;Rank&#45;Adaptation.
