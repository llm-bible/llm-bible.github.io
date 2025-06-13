---
layout: publication
title: 'Bypassing The Exponential Dependency: Looped Transformers Efficiently Learn In-context By Multi-step Gradient Descent'
authors: Bo Chen, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song
conference: "Arxiv"
year: 2024
bibkey: chen2024bypassing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11268"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
In-context learning has been recognized as a key factor in the success of
Large Language Models (LLMs). It refers to the model's ability to learn
patterns on the fly from provided in-context examples in the prompt during
inference. Previous studies have demonstrated that the Transformer architecture
used in LLMs can implement a single-step gradient descent update by processing
in-context examples in a single forward pass. Recent work has further shown
that, during in-context learning, a looped Transformer can implement multi-step
gradient descent updates in forward passes. However, their theoretical results
require an exponential number of in-context examples, \\(n = \exp(Ω(T))\\),
where \\(T\\) is the number of loops or passes, to achieve a reasonably low error.
In this paper, we study linear looped Transformers in-context learning on
linear vector generation tasks. We show that linear looped Transformers can
implement multi-step gradient descent efficiently for in-context learning. Our
results demonstrate that as long as the input data has a constant condition
number, e.g., \\(n = O(d)\\), the linear looped Transformers can achieve a small
error by multi-step gradient descent during in-context learning. Furthermore,
our preliminary experiments validate our theoretical analysis. Our findings
reveal that the Transformer architecture possesses a stronger in-context
learning capability than previously understood, offering new insights into the
mechanisms behind LLMs and potentially guiding the better design of efficient
inference algorithms for LLMs.
