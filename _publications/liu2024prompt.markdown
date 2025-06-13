---
layout: publication
title: 'PLPP: Prompt Learning With Perplexity Is Self-distillation For Vision-language Models'
authors: Biao Liu, Wenyi Fang, Xiaoyu Wu, Yang Zheng, Zheng Hu, Bo Yuan
conference: "Arxiv"
year: 2024
bibkey: liu2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15277"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Distillation', 'Prompting']
---
Pre-trained Vision-Language (VL) models such as CLIP have demonstrated their
excellent performance across numerous downstream tasks. A recent method,
Context Optimization (CoOp), further improves the performance of VL models on
downstream tasks by introducing prompt learning. CoOp optimizes a set of
learnable vectors, aka prompt, and freezes the whole CLIP model. However,
relying solely on CLIP loss to fine-tune prompts can lead to models that are
prone to overfitting on downstream task. To address this issue, we propose a
plug-in prompt-regularization method called PLPP (Prompt Learning with
PerPlexity), which use perplexity loss to regularize prompt learning. PLPP
designs a two-step operation to compute the perplexity for prompts: (a)
calculating cosine similarity between the weight of the embedding layer and
prompts to get labels, (b) introducing a language model (LM) head that requires
no training behind text encoder to output word probability distribution.
Meanwhile, we unveil that the essence of PLPP is inherently a form of
self-distillation. To further prevent overfitting as well as to reduce the
additional computation introduced by PLPP, we turn the hard label to soft label
and choose top-\\(k\\) values for calculating the perplexity loss. For accelerating
model convergence, we introduce mutual self-distillation learning, that is
perplexity and inverted perplexity loss. The experiments conducted on four
classification tasks indicate that PLPP exhibits superior performance compared
to existing methods.
