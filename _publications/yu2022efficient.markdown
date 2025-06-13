---
layout: publication
title: 'Efficient Language Modeling With Sparse All-mlp'
authors: Ping Yu, Mikel Artetxe, Myle Ott, Sam Shleifer, Hongyu Gong, Ves Stoyanov, Xian Li
conference: "Arxiv"
year: 2022
bibkey: yu2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.06850"}
tags: ['Transformer', 'Efficiency and Optimization', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
All-MLP architectures have attracted increasing interest as an alternative to
attention-based models. In NLP, recent work like gMLP shows that all-MLPs can
match Transformers in language modeling, but still lag behind in downstream
tasks. In this work, we analyze the limitations of MLPs in expressiveness, and
propose sparsely activated MLPs with mixture-of-experts (MoEs) in both feature
and input (token) dimensions. Such sparse all-MLPs significantly increase model
capacity and expressiveness while keeping the compute constant. We address
critical challenges in incorporating conditional computation with two routing
strategies. The proposed sparse all-MLP improves language modeling perplexity
and obtains up to 2\\(\times\\) improvement in training efficiency compared to both
Transformer-based MoEs (GShard, Switch Transformer, Base Layers and HASH
Layers) as well as dense Transformers and all-MLPs. Finally, we evaluate its
zero-shot in-context learning performance on six downstream tasks, and find
that it surpasses Transformer-based MoEs and dense Transformers.
