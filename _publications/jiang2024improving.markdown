---
layout: publication
title: 'Improving Domain Adaptation Through Extended-text Reading Comprehension'
authors: Ting Jiang, Shaohan Huang, Shengyue Luo, Zihan Zhang, Haizhen Huang, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Deqing Wang, Fuzhen Zhuang
conference: "Arxiv"
year: 2024
bibkey: jiang2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.07284'}
  - {name: "Code", url: 'https://github.com/microsoft/LMOps'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
To enhance the domain-specific capabilities of large language models,
continued pre-training on a domain-specific corpus is a prevalent method.
Recent work demonstrates that adapting models using reading comprehension data
formatted by regex-based patterns can significantly improve performance on
domain-specific tasks. However, regex-based patterns are incapable of parsing
raw corpora using domain-specific knowledge. Furthermore, the question and
answer pairs are extracted directly from the corpus in predefined formats
offers limited context. To address this limitation, we improve reading
comprehension via LLM and clustering. LLM focuses on leveraging domain
knowledge within the corpus to refine comprehension stage, while clustering
supplies relevant knowledge by extending the context to enrich reading stage.
Additionally, our method incorporates parameter-efficient fine-tuning to
improve the efficiency of domain adaptation. In comparison to AdaptLLM, our
method achieves an improvement exceeding 5% in domain-specific tasks. Our code
will available at https://github.com/microsoft/LMOps.
