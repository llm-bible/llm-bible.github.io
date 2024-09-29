---
layout: publication
title: Understand What LLM Needs Dual Preference Alignment For Retrieval45;augmented Generation
authors: Dong Guanting, Zhu Yutao, Zhang Chenghao, Wang Zechen, Dou Zhicheng, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: dong2024understand
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18676"}
  - {name: "Code", url: "https://github.com/dongguanting/DPA&#45;RAG"}
tags: ['Fine Tuning', 'Has Code', 'RAG', 'Tools']
---
Retrieval45;augmented generation (RAG) has demonstrated effectiveness in mitigating the hallucination problem of large language models (LLMs). However the difficulty of aligning the retriever with the diverse LLMs knowledge preferences inevitably poses an inevitable challenge in developing a reliable RAG system. To address this issue we propose DPA45;RAG a universal framework designed to align diverse knowledge preferences within RAG systems. Specifically we initially introduce a preference knowledge construction pipline and incorporate five novel query augmentation strategies to alleviate preference data scarcity. Based on preference data DPA45;RAG accomplishes both external and internal preference alignment 1) It jointly integrate pair45;wise point45;wise and contrastive preference alignment abilities into the reranker achieving external preference alignment among RAG components. 2) It further introduces a pre45;aligned stage before vanilla Supervised Fine45;tuning (SFT) enabling LLMs to implicitly capture knowledge aligned with their reasoning preferences achieving LLMs internal alignment. Experimental results across four knowledge45;intensive QA datasets demonstrate that DPA45;RAG outperforms all baselines and seamlessly integrates both black45;box and open45;sourced LLM readers. Further qualitative analysis and discussions also provide empirical guidance for achieving reliable RAG systems. Our code is publicly available at https://github.com/dongguanting/DPA&#45;RAG.
