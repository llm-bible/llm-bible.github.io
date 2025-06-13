---
layout: publication
title: 'Pdf-wukong: A Large Multimodal Model For Efficient Long PDF Reading With End-to-end Sparse Sampling'
authors: Xudong Xie, Hao Yan, Liang Yin, Yang Liu, Jing Ding, Minghui Liao, Yuliang Liu, Wei Chen, Xiang Bai
conference: "Arxiv"
year: 2024
bibkey: xie2024pdf
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05970'}
  - {name: "Code", url: 'https://github.com/yh-hust/PDF-Wukong'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal document understanding is a challenging task to process and
comprehend large amounts of textual and visual information. Recent advances in
Large Language Models (LLMs) have significantly improved the performance of
this task. However, existing methods typically focus on either plain text or a
limited number of document images, struggling to handle long PDF documents with
interleaved text and images, especially for academic papers. In this paper, we
introduce PDF-WuKong, a multimodal large language model (MLLM) which is
designed to enhance multimodal question-answering (QA) for long PDF documents.
PDF-WuKong incorporates a sparse sampler that operates on both text and image
representations, significantly improving the efficiency and capability of the
MLLM. The sparse sampler is integrated with the MLLM's image encoder and
selects the paragraphs or diagrams most pertinent to user queries for
processing by the language model. To effectively train and evaluate our model,
we construct PaperPDF, a dataset consisting of a broad collection of English
and Chinese academic papers. Multiple strategies are proposed to automatically
generate 1.1 million QA pairs along with their corresponding evidence sources.
Experimental results demonstrate the superiority and high efficiency of our
approach over other models on the task of long multimodal document
understanding, surpassing proprietary products by an average of 8.6% on F1. Our
code and dataset will be released at https://github.com/yh-hust/PDF-Wukong.
