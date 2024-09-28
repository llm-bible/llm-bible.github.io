---
layout: publication
title: SnapNTell Enhancing Entity-Centric Visual Question Answering with Retrieval Augmented Multimodal LLM
authors: Qiu Jielin, Madotto Andrea, Lin Zhaojiang, Crook Paul A., Xu Yifan Ethan, Dong Xin Luna, Faloutsos Christos, Li Lei, Damavandi Babak, Moon Seungwhan
conference: "Arxiv"
year: 2024
bibkey: qiu2024snapntell
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04735"}
tags: ['LLM', 'Multimodal Models', 'Arxiv']
---
Vision-extended LLMs have made significant strides in Visual Question Answering (VQA). Despite these advancements VLLMs still encounter substantial difficulties in handling queries involving long-tail entities with a tendency to produce erroneous or hallucinated responses. In this work we introduce a novel evaluative benchmark named specifically tailored for entity-centric VQA. This task aims to test the models capabilities in identifying entities and providing detailed entity-specific knowledge. We have developed the distinct from traditional VQA datasets (1) It encompasses a wide range of categorized entities each represented by images and explicitly named in the answers; (2) It features QA pairs that require extensive knowledge for accurate responses. The dataset is organized into 22 major categories containing 7568 unique entities in total. For each entity we curated 10 illustrative images and crafted 10 knowledge-intensive QA pairs. To address this novel task we devised a scalable efficient and transparent retrieval-augmented multimodal LLM. Our approach markedly outperforms existing methods on the SnapNTell dataset achieving a 66.5 improvement in the BELURT score. We will soon make the dataset and the source code publicly accessible.
