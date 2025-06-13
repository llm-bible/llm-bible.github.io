---
layout: publication
title: 'Chinesewebtext 2.0: Large-scale High-quality Chinese Web Text With Multi-dimensional And Fine-grained Information'
authors: Wanyue Zhang, Ziyong Li, Wen Yang, Chunlin Leng, Yinan Bai, Qianlong Du, Chengqing Zong, Jiajun Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024chinesewebtext
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19668'}
  - {name: "Code", url: 'https://github.com/CASIA-LM/ChineseWebText-2.0'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Pre-Training', 'Responsible AI']
---
During the development of large language models (LLMs), pre-training data
play a critical role in shaping LLMs' capabilities. In recent years several
large-scale and high-quality pre-training datasets have been released to
accelerate the research of LLMs, including ChineseWebText1.0, C4, Pile,
WanJuan, MAPCC and others. However, as LLMs continue to evolve, focus has
increasingly shifted to domain-specific capabilities and safety concerns,
making those previous coarse-grained texts insufficient for meeting training
requirements. Furthermore, fine-grained information, such as quality, domain
and toxicity, is becoming increasingly important in building powerful and
reliable LLMs for various scenarios. To address these challenges, in this paper
we propose a new tool-chain called MDFG-tool for constructing large-scale and
high-quality Chinese datasets with multi-dimensional and fine-grained
information. First, we employ manually crafted rules to discard explicit noisy
texts from raw contents. Second, the quality evaluation model, domain
classifier, and toxicity evaluation model are well-designed to assess the
remaining cleaned data respectively. Finally, we integrate these three types of
fine-grained information for each text. With this approach, we release the
largest, high-quality and fine-grained Chinese text ChineseWebText2.0, which
consists of 3.8TB and each text is associated with a quality score, domain
labels, a toxicity label and a toxicity score, facilitating the LLM researchers
to select data based on various types of fine-grained information. The data,
codes and the tool-chain are available on this website
https://github.com/CASIA-LM/ChineseWebText-2.0
