---
layout: publication
title: 'Customized Retrieval Augmented Generation And Benchmarking For EDA Tool Documentation QA'
authors: Pu Yuan, He Zhuolun, Qiu Tairu, Wu Haoyuan, Yu Bei
conference: "Arxiv"
year: 2024
bibkey: pu2024customized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15353"}
  - {name: "Code", url: "https://github.com/lesliepy99/RAG-EDA"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
'Retrieval augmented generation (RAG) enhances the accuracy and reliability of generative AI models by sourcing factual information from external databases, which is extensively employed in document-grounded question-answering (QA) tasks. Off-the-shelf RAG flows are well pretrained on general-purpose documents, yet they encounter significant challenges when being applied to knowledge-intensive vertical domains, such as electronic design automation (EDA). This paper addresses such issue by proposing a customized RAG framework along with three domain-specific techniques for EDA tool documentation QA, including a contrastive learning scheme for text embedding model fine-tuning, a reranker distilled from proprietary LLM, and a generative LLM fine-tuned with high-quality domain corpus. Furthermore, we have developed and released a documentation QA evaluation benchmark, ORD-QA, for OpenROAD, an advanced RTL-to-GDSII design platform. Experimental results demonstrate that our proposed RAG flow and techniques have achieved superior performance on ORD-QA as well as on a commercial tool, compared with state-of-the-arts. The ORD-QA benchmark and the training dataset for our customized RAG flow are open-source at https://github.com/lesliepy99/RAG-EDA.'
