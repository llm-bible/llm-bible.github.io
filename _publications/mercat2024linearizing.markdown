---
layout: publication
title: Linearizing Large Language Models
authors: Mercat Jean, Vasiljevic Igor, Keh Sedrick, Arora Kushal, Dave Achal, Gaidon Adrien, Kollar Thomas
conference: "Arxiv"
year: 2024
bibkey: mercat2024linearizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06640"}
  - {name: "Code", url: "https://github.com/TRI&#45;ML/linear&#95;open&#95;lm"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Linear transformers have emerged as a subquadratic45;time alternative to softmax attention and have garnered significant interest due to their fixed45;size recurrent state that lowers inference cost. However their original formulation suffers from poor scaling and underperforms compute45;matched transformers. Recent linear models such as RWKV and Mamba have attempted to address these shortcomings by proposing novel time45;mixing and gating architectures but pre45;training large language models requires significant data and compute investments. Thus the search for subquadratic architectures is limited by the availability of compute and quality pre45;training datasets. As a cost45;effective alternative to pre45;training linear transformers we propose Scalable UPtraining for Recurrent Attention (SUPRA). We present a method to uptrain existing large pre45;trained transformers into Recurrent Neural Networks (RNNs) with a modest compute budget. This allows us to leverage the strong pre45;training data and performance of existing transformer LLMs while requiring 537; of the training cost. We find that our linearization technique leads to competitive performance on standard benchmarks but we identify persistent in45;context learning and long45;context modeling shortfalls for even the largest linear models. Our code and models can be found at https://github.com/TRI&#45;ML/linear&#95;open&#95;lm.
