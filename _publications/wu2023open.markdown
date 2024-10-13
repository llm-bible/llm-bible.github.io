---
layout: publication
title: 'Openicl: An Open-source Framework For In-context Learning'
authors: Wu Zhenyu, Wang Yaoxiang, Ye Jiacheng, Feng Jiangtao, Xu Jingjing, Qiao Yu, Wu Zhiyong
conference: "Arxiv"
year: 2023
bibkey: wu2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.02913"}
  - {name: "Code", url: "https://github.com/Shark-NLP/OpenICL"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
In recent years, In-context Learning (ICL) has gained increasing attention
and emerged as the new paradigm for large language model (LLM) evaluation.
Unlike traditional fine-tuning methods, ICL instead adapts the pre-trained
models to unseen tasks without any parameter updates. However, the
implementation of ICL is sophisticated due to the diverse retrieval and
inference methods involved, as well as the varying pre-processing requirements
for different models, datasets, and tasks. A unified and flexible framework for
ICL is urgently needed to ease the implementation of the aforementioned
components. To facilitate ICL research, we introduce OpenICL, an open-source
toolkit for ICL and LLM evaluation. OpenICL is research-friendly with a highly
flexible architecture that users can easily combine different components to
suit their needs. It also provides various state-of-the-art retrieval and
inference methods to streamline the process of adapting ICL to cutting-edge
research. The effectiveness of OpenICL has been validated on a wide range of
NLP tasks, including classification, QA, machine translation, and semantic
parsing. As a side-product, we found OpenICL to be an efficient yet robust tool
for LLMs evaluation. OpenICL is released at
https://github.com/Shark-NLP/OpenICL
