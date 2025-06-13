---
layout: publication
title: 'Deformer: Decomposing Pre-trained Transformers For Faster Question Answering'
authors: Qingqing Cao, Harsh Trivedi, Aruna Balasubramanian, Niranjan Balasubramanian
conference: "Arxiv"
year: 2020
bibkey: cao2020decomposing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00697"}
  - {name: "Code", url: "https://github.com/StonyBrookNLP/deformer"}
tags: ['Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'BERT', 'Distillation']
---
Transformer-based QA models use input-wide self-attention -- i.e. across both
the question and the input passage -- at all layers, causing them to be slow
and memory-intensive. It turns out that we can get by without input-wide
self-attention at all layers, especially in the lower layers. We introduce
DeFormer, a decomposed transformer, which substitutes the full self-attention
with question-wide and passage-wide self-attentions in the lower layers. This
allows for question-independent processing of the input text representations,
which in turn enables pre-computing passage representations reducing runtime
compute drastically. Furthermore, because DeFormer is largely similar to the
original model, we can initialize DeFormer with the pre-training weights of a
standard transformer, and directly fine-tune on the target QA dataset. We show
DeFormer versions of BERT and XLNet can be used to speed up QA by over 4.3x and
with simple distillation-based losses they incur only a 1% drop in accuracy. We
open source the code at https://github.com/StonyBrookNLP/deformer.
