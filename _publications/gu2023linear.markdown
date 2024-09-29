---
layout: publication
title: Mamba Linear45;time Sequence Modeling With Selective State Spaces
authors: Albert Gu, Tri Dao
conference: "Arxiv"
year: 2023
bibkey: gu2023linear
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2312.00752v2"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Foundation models now powering most of the exciting applications in deep learning are almost universally based on the Transformer architecture and its core attention module. Many subquadratic45;time architectures such as linear attention gated convolution and recurrent models and structured state space models (SSMs) have been developed to address Transformers computational inefficiency on long sequences but they have not performed as well as attention on important modalities such as language. We identify that a key weakness of such models is their inability to perform content45;based reasoning and make several improvements. First simply letting the SSM parameters be functions of the input addresses their weakness with discrete modalities allowing the model to selectively propagate or forget information along the sequence length dimension depending on the current token. Second even though this change prevents the use of efficient convolutions we design a hardware45;aware parallel algorithm in recurrent mode. We integrate these selective SSMs into a simplified end45;to45;end neural network architecture without attention or even MLP blocks (Mamba). Mamba enjoys fast inference (5× higher throughput than Transformers) and linear scaling in sequence length and its performance improves on real data up to million45;length sequences. As a general sequence model backbone Mamba achieves state45;of45;the45;art performance across several modalities such as language audio and genomics. On language modeling our Mamba45;3B model outperforms Transformers of the same size and matches Transformers twice its size both in pretraining and downstream evaluation.
