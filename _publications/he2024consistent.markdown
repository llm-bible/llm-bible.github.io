---
layout: publication
title: 'CPT: Consistent Proxy Tuning For Black-box Optimization'
authors: Yuanyang He, Zitong Huang, Xinxing Xu, Rick Siow Mong Goh, Salman Khan, Wangmeng Zuo, Yong Liu, Chun-mei Feng
conference: "Arxiv"
year: 2024
bibkey: he2024consistent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01155"}
  - {name: "Code", url: "https://github.com/chunmeifeng/CPT"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Has Code', 'Attention Mechanism']
---
Black-box tuning has attracted recent attention due to that the structure or
inner parameters of advanced proprietary models are not accessible.
Proxy-tuning provides a test-time output adjustment for tuning black-box
language models. It applies the difference of the output logits before and
after tuning a smaller white-box "proxy" model to improve the black-box model.
However, this technique serves only as a decoding-time algorithm, leading to an
inconsistency between training and testing which potentially limits overall
performance. To address this problem, we introduce Consistent Proxy Tuning
(CPT), a simple yet effective black-box tuning method. Different from
Proxy-tuning, CPT additionally exploits the frozen large black-box model and
another frozen small white-box model, ensuring consistency between
training-stage optimization objective and test-time proxies. This consistency
benefits Proxy-tuning and enhances model performance. Note that our method
focuses solely on logit-level computation, which makes it model-agnostic and
applicable to any task involving logit classification. Extensive experimental
results demonstrate the superiority of our CPT in both black-box tuning of
Large Language Models (LLMs) and Vision-Language Models (VLMs) across various
datasets. The code is available at https://github.com/chunmeifeng/CPT.
