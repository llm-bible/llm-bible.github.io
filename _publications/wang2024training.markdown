---
layout: publication
title: 'XL3M: A Training-free Framework For LLM Length Extension Based On Segment-wise Inference'
authors: Shengnan Wang, Youhui Bai, Lin Zhang, Pingyi Zhou, Shixiong Zhao, Gong Zhang, Sen Wang, Renhai Chen, Hua Xu, Hongwei Sun
conference: "Arxiv"
year: 2024
bibkey: wang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17755"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Tools']
---
Length generalization failure problem, namely the large language model (LLM)
fails to generalize to texts longer than its maximum training length, greatly
restricts the application of LLM in the scenarios with streaming long inputs.
To address this problem, the existing methods either require substantial costs
or introduce precision loss. In this paper, we empirically find that the
accuracy of the LLM's prediction is highly correlated to its certainty. Based
on this, we propose an efficient training free framework, named XL3M (it means
extra-long large language model), which enables the LLMs trained on short
sequences to reason extremely long sequence without any further training or
fine-tuning. Under the XL3M framework, the input context will be firstly
decomposed into multiple short sub-contexts, where each sub-context contains an
independent segment and a common ``question'' which is a few tokens from the
end of the original context. Then XL3M gives a method to measure the relevance
between each segment and the ``question'', and constructs a concise key context
by splicing all the relevant segments in chronological order. The key context
is further used instead of the original context to complete the inference task.
Evaluations on comprehensive benchmarks show the superiority of XL3M. Using our
framework, a Llama2-7B model is able to reason 20M long sequences on an 8-card
Huawei Ascend 910B NPU machine with 64GB memory per card.
