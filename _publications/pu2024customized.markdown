---
layout: publication
title: Customized Retrieval Augmented Generation And Benchmarking For EDA Tool Documentation QA
authors: Pu Yuan, He Zhuolun, Qiu Tairu, Wu Haoyuan, Yu Bei
conference: "Arxiv"
year: 2024
bibkey: pu2024customized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15353"}
  - {name: "Code", url: "https://github.com/lesliepy99/RAG&#45;EDA"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Retrieval augmented generation (RAG) enhances the accuracy and reliability of generative AI models by sourcing factual information from external databases which is extensively employed in document45;grounded question45;answering (QA) tasks. Off45;the45;shelf RAG flows are well pretrained on general45;purpose documents yet they encounter significant challenges when being applied to knowledge45;intensive vertical domains such as electronic design automation (EDA). This paper addresses such issue by proposing a customized RAG framework along with three domain45;specific techniques for EDA tool documentation QA including a contrastive learning scheme for text embedding model fine45;tuning a reranker distilled from proprietary LLM and a generative LLM fine45;tuned with high45;quality domain corpus. Furthermore we have developed and released a documentation QA evaluation benchmark ORD45;QA for OpenROAD an advanced RTL45;to45;GDSII design platform. Experimental results demonstrate that our proposed RAG flow and techniques have achieved superior performance on ORD45;QA as well as on a commercial tool compared with state45;of45;the45;arts. The ORD45;QA benchmark and the training dataset for our customized RAG flow are open45;source at https://github.com/lesliepy99/RAG&#45;EDA.
