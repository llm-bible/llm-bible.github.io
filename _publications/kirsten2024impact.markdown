---
layout: publication
title: 'The Impact Of Inference Acceleration On Bias Of Llms'
authors: Elisabeth Kirsten, Ivan Habernal, Vedant Nanda, Muhammad Bilal Zafar
conference: "Arxiv"
year: 2024
bibkey: kirsten2024impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22118"}
tags: ['Efficiency and Optimization', 'Quantization', 'Pruning', 'Ethics and Bias']
---
Last few years have seen unprecedented advances in capabilities of Large
Language Models (LLMs). These advancements promise to benefit a vast array of
application domains. However, due to their immense size, performing inference
with LLMs is both costly and slow. Consequently, a plethora of recent work has
proposed strategies to enhance inference efficiency, e.g., quantization,
pruning, and caching. These acceleration strategies reduce the inference cost
and latency, often by several factors, while maintaining much of the predictive
performance measured via common benchmarks. In this work, we explore another
critical aspect of LLM performance: demographic bias in model generations due
to inference acceleration optimizations. Using a wide range of metrics, we
probe bias in model outputs from a number of angles. Analysis of outputs before
and after inference acceleration shows significant change in bias. Worryingly,
these bias effects are complex and unpredictable. A combination of an
acceleration strategy and bias type may show little bias change in one model
but may lead to a large effect in another. Our results highlight a need for
in-depth and case-by-case evaluation of model bias after it has been modified
to accelerate inference.
