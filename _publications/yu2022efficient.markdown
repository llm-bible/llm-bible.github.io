---
layout: publication
title: Efficient Language Modeling With Sparse All45;mlp
authors: Yu Ping, Artetxe Mikel, Ott Myle, Shleifer Sam, Gong Hongyu, Stoyanov Ves, Li Xian
conference: "Arxiv"
year: 2022
bibkey: yu2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.06850"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
All45;MLP architectures have attracted increasing interest as an alternative to attention45;based models. In NLP recent work like gMLP shows that all45;MLPs can match Transformers in language modeling but still lag behind in downstream tasks. In this work we analyze the limitations of MLPs in expressiveness and propose sparsely activated MLPs with mixture45;of45;experts (MoEs) in both feature and input (token) dimensions. Such sparse all45;MLPs significantly increase model capacity and expressiveness while keeping the compute constant. We address critical challenges in incorporating conditional computation with two routing strategies. The proposed sparse all45;MLP improves language modeling perplexity and obtains up to 2× improvement in training efficiency compared to both Transformer45;based MoEs (GShard Switch Transformer Base Layers and HASH Layers) as well as dense Transformers and all45;MLPs. Finally we evaluate its zero45;shot in45;context learning performance on six downstream tasks and find that it surpasses Transformer45;based MoEs and dense Transformers.
