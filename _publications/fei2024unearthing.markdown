---
layout: publication
title: 'Unearthing Large Scale Domain-specific Knowledge From Public Corpora'
authors: Zhaoye Fei, Yunfan Shao, Linyang Li, Zhiyuan Zeng, Conghui He, Qipeng Guo, Hang Yan, Dahua Lin, Xipeng Qiu
conference: "Arxiv"
year: 2024
bibkey: fei2024unearthing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.14624'}
tags: ['Uncategorized']
---
Large language models (LLMs) have demonstrated remarkable potential in various tasks, however, there remains a significant lack of open-source models and data for specific domains. Previous work has primarily focused on manually specifying resources and collecting high-quality data for specific domains, which is extremely time-consuming and labor-intensive. To address this limitation, we introduce large models into the data collection pipeline to guide the generation of domain-specific information and retrieve relevant data from Common Crawl (CC), a large public corpus. We refer to this approach as Retrieve-from-CC. It not only collects data related to domain-specific knowledge but also mines the data containing potential reasoning procedures from the public corpus. By applying this method, we have collected a knowledge domain-related dataset named Retrieve-Pile, which covers four main domains, including the sciences, humanities, and other categories. Through the analysis of , Retrieve-from-CC can effectively retrieve relevant data from the covered knowledge domains and significantly improve the performance in tests of mathematical and knowledge-related reasoning abilities. We have released Retrieve-Pile at https://huggingface.co/datasets/Query-of-CC/Retrieve-Pile.
