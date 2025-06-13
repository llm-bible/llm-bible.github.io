---
layout: publication
title: 'MMM: Multilingual Mutual Reinforcement Effect Mix Datasets & Test With Open-domain Information Extraction Large Language Models'
authors: Chengguang Gan, Sunbowen Lee, Qingyu Yin, Xinyang He, Hanjun Wei, Yunhao Liang, Younghun Lim, Shijian Wang, Hexiang Huang, Qinghao Zhang, Shiwen Ni, Tatsunori Mori
conference: "Arxiv"
year: 2024
bibkey: gan2024multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.10953'}
tags: ['RAG', 'Fine-Tuning', 'Tools']
---
The Mutual Reinforcement Effect (MRE) represents a promising avenue in
information extraction and multitasking research. Nevertheless, its
applicability has been constrained due to the exclusive availability of MRE mix
datasets in Japanese, thereby limiting comprehensive exploration by the global
research community. To address this limitation, we introduce a Multilingual MRE
mix dataset (MMM) that encompasses 21 sub-datasets in English, Japanese, and
Chinese. In this paper, we also propose a method for dataset translation
assisted by Large Language Models (LLMs), which significantly reduces the
manual annotation time required for dataset construction by leveraging LLMs to
translate the original Japanese datasets. Additionally, we have enriched the
dataset by incorporating open-domain Named Entity Recognition (NER) and
sentence classification tasks. Utilizing this expanded dataset, we developed a
unified input-output framework to train an Open-domain Information Extraction
Large Language Model (OIELLM). The OIELLM model demonstrates the capability to
effectively process novel MMM datasets, exhibiting significant improvements in
performance. The OIELLM model and datasets is open-source in HuggingFace:
https://ganchengguang.github.io/MRE/
