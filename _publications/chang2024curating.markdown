---
layout: publication
title: 'Redstone: Curating General, Code, Math, And QA Data For Large Language Models'
authors: Yaoyao Chang, Lei Cui, Li Dong, Shaohan Huang, Yangyu Huang, Yupan Huang, Scarlett Li, Tengchao Lv, Shuming Ma, Qinzheng Sun, Wenhui Wang, Furu Wei, Ying Xin, Mao Yang, Qiufeng Yin, Xingxing Zhang
conference: "Arxiv"
year: 2024
bibkey: chang2024curating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03398'}
  - {name: "Code", url: 'https://aka.ms/redstone'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Reinforcement Learning', 'Pre-Training']
---
Pre-training Large Language Models (LLMs) on high-quality, meticulously
curated datasets is widely recognized as critical for enhancing their
performance and generalization capabilities. This study explores the untapped
potential of Common Crawl as a comprehensive and flexible resource for
pre-training LLMs, addressing both general-purpose language understanding and
specialized domain knowledge. We introduce RedStone, an innovative and scalable
pipeline engineered to extract and process data from Common Crawl, facilitating
the creation of extensive and varied pre-training datasets. Unlike traditional
datasets, which often require expensive curation and domain-specific expertise,
RedStone leverages the breadth of Common Crawl to deliver datasets tailored to
a wide array of domains. In this work, we exemplify its capability by
constructing pre-training datasets across multiple fields, including general
language understanding, code, mathematics, and question-answering tasks. The
flexibility of RedStone allows for easy adaptation to other specialized
domains, significantly lowering the barrier to creating valuable
domain-specific datasets. Our findings demonstrate that Common Crawl, when
harnessed through effective pipelines like RedStone, can serve as a rich,
renewable source of pre-training data, unlocking new avenues for domain
adaptation and knowledge discovery in LLMs. This work also underscores the
importance of innovative data acquisition strategies and highlights the role of
web-scale data as a powerful resource in the continued evolution of LLMs.
RedStone code and data samples will be publicly available at
\url\{https://aka.ms/redstone\}.
