---
layout: publication
title: 'Advancing Precise Outline-conditioned Text Generation With Task Duality And Explicit Outline Control'
authors: Yunzhe Li, Qian Chen, Weixiang Yan, Wen Wang, Qinglin Zhang, Hari Sundaram
conference: "Arxiv"
year: 2023
bibkey: li2023advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14459"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Existing works on outline-conditioned text generation typically aim to
generate text using provided outlines as rough sketches, such as keywords and
phrases. However, these approaches make it challenging to control the quality
of text generation and assess consistency between outlines and generated texts
due to lack of clarity and rationality of the rough outlines. In this paper, we
introduce a novel text generation task called Precise Outline-conditioned
Generation, which requires generating stories based on specific, sentence-level
outlines. To facilitate research on this task, we construct two new datasets,
WPOG and CDM. We provide strong baselines based on fine-tuning models such as
BART and GPT-2, and evaluating zero-shot performance of models such as ChatGPT
and Vicuna. Furthermore, we identify an issue of imbalanced utilization of the
outline information in the precise outline-conditioned generation, which is
ubiquitously observed across fine-tuned models and zero-shot inference models.
To address this issue, we propose an explicit outline utilization control
approach and a novel framework that leverages the task duality between
summarization and generation. Experimental results show that the proposed
approaches effectively alleviate the issue of imbalanced outline utilization
and enhance the quality of precise outline-conditioned text generation for both
fine-tuning and zero-shot settings.
