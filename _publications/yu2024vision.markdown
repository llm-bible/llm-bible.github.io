---
layout: publication
title: 'Visrag: Vision-based Retrieval-augmented Generation On Multi-modality Documents'
authors: Shi Yu, Chaoyue Tang, Bokai Xu, Junbo Cui, Junhao Ran, Yukun Yan, Zhenghao Liu, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: yu2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10594"}
  - {name: "Code", url: "https://github.com/openbmb/visrag"}
tags: ['RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Retrieval-augmented generation (RAG) is an effective technique that enables
large language models (LLMs) to utilize external knowledge sources for
generation. However, current RAG systems are solely based on text, rendering it
impossible to utilize vision information like layout and images that play
crucial roles in real-world multi-modality documents. In this paper, we
introduce VisRAG, which tackles this issue by establishing a vision-language
model (VLM)-based RAG pipeline. In this pipeline, instead of first parsing the
document to obtain text, the document is directly embedded using a VLM as an
image and then retrieved to enhance the generation of a VLM. Compared to
traditional text-based RAG, VisRAG maximizes the retention and utilization of
the data information in the original documents, eliminating the information
loss introduced during the parsing process. We collect both open-source and
synthetic data to train the retriever in VisRAG and explore a variety of
generation methods. Experiments demonstrate that VisRAG outperforms traditional
RAG in both the retrieval and generation stages, achieving a 20--40% end-to-end
performance gain over traditional text-based RAG pipeline. Further analysis
reveals that VisRAG is efficient in utilizing training data and demonstrates
strong generalization capability, positioning it as a promising solution for
RAG on multi-modality documents. Our code and data are available at
https://github.com/openbmb/visrag.
