---
layout: publication
title: Enabling Natural Zero45;shot Prompting On Encoder Models Via Statement45;tuning
authors: Elshabrawy Ahmed, Huang Yongxin, Gurevych Iryna, Aji Alham Fikri
conference: "Arxiv"
year: 2024
bibkey: elshabrawy2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12897"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
While Large Language Models (LLMs) exhibit remarkable capabilities in zero45;shot and few45;shot scenarios they often require computationally prohibitive sizes. Conversely smaller Masked Language Models (MLMs) like BERT and RoBERTa achieve state45;of45;the45;art results through fine45;tuning but struggle with extending to few45;shot and zero45;shot settings due to their architectural constraints. Hence we propose Statement45;Tuning a technique that models discriminative tasks as a set of finite statements and trains an Encoder model to discriminate between the potential statements to determine the label. We do Statement45;Tuning on multiple tasks to enable cross45;task generalization. Experimental results demonstrate that Statement Tuning achieves competitive performance compared to state45;of45;the45;art LLMs with significantly fewer parameters. Moreover the study investigates the impact of several design choices on few45;shot and zero45;shot generalization revealing that Statement Tuning can achieve sufficient performance with modest training data and benefits from task and statement diversity for unseen task generalizability.
