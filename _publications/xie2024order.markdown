---
layout: publication
title: 'Coral: Order-agnostic Language Modeling For Efficient Iterative Refinement'
authors: Yuxi Xie, Anirudh Goyal, Xiaobao Wu, Xunjian Yin, Xiao Xu, Min-yen Kan, Liangming Pan, William Yang Wang
conference: "Arxiv"
year: 2024
bibkey: xie2024order
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09675"}
  - {name: "Code", url: "https://github.com/YuxiXie/COrAL"}
tags: ['Efficiency and Optimization', 'GPT', 'Applications', 'RAG', 'Language Modeling', 'Model Architecture', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Iterative refinement has emerged as an effective paradigm for enhancing the
capabilities of large language models (LLMs) on complex tasks. However,
existing approaches typically implement iterative refinement at the application
or prompting level, relying on autoregressive (AR) modeling. The sequential
token generation in AR models can lead to high inference latency. To overcome
these challenges, we propose Context-Wise Order-Agnostic Language Modeling
(COrAL), which incorporates iterative refinement directly into the LLM
architecture while maintaining computational efficiency. Our approach models
multiple token dependencies within manageable context windows, enabling the
model to perform iterative refinement internally during the generation process.
Leveraging the order-agnostic nature of COrAL, we introduce sliding blockwise
order-agnostic decoding, which performs multi-token forward prediction and
backward reconstruction within context windows. This allows the model to
iteratively refine its outputs in parallel in the sliding block, effectively
capturing diverse dependencies without the high inference cost of sequential
generation. Empirical evaluations on reasoning tasks demonstrate that COrAL
improves performance and inference speed, respectively, achieving absolute
accuracy gains of \\(4.6%\\) on GSM8K and \\(4.0%\\) on LogiQA, along with inference
speedups of up to \\(3.9\times\\) over next-token baselines. Preliminary results on
code generation indicate a drop in pass rates due to inconsistencies in
order-agnostic outputs, highlighting the inherent quality--speed trade-off. Our
code is publicly available at https://github.com/YuxiXie/COrAL.
