---
layout: publication
title: 'Mechanism And Emergence Of Stacked Attention Heads In Multi-layer Transformers'
authors: Tiberiu Musat
conference: "Arxiv"
year: 2024
bibkey: musat2024mechanism
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12118"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
In this paper, I introduce the retrieval problem, a simple yet common
reasoning task that can be solved only by transformers with a minimum number of
layers, which grows logarithmically with the input size. I empirically show
that large language models can solve the task under different prompting
formulations without any fine-tuning. To understand how transformers solve the
retrieval problem, I train several transformers on a minimal formulation.
Successful learning occurs only under the presence of an implicit curriculum. I
uncover the learned mechanisms by studying the attention maps in the trained
transformers. I also study the training process, uncovering that attention
heads always emerge in a specific sequence guided by the implicit curriculum.
