---
layout: publication
title: Advancing Precise Outline45;conditioned Text Generation With Task Duality And Explicit Outline Control
authors: Li Yunzhe, Chen Qian, Yan Weixiang, Wang Wen, Zhang Qinglin, Sundaram Hari
conference: "Arxiv"
year: 2023
bibkey: li2023advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14459"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Tools']
---
Existing works on outline45;conditioned text generation typically aim to generate text using provided outlines as rough sketches such as keywords and phrases. However these approaches make it challenging to control the quality of text generation and assess consistency between outlines and generated texts due to lack of clarity and rationality of the rough outlines. In this paper we introduce a novel text generation task called Precise Outline45;conditioned Generation which requires generating stories based on specific sentence45;level outlines. To facilitate research on this task we construct two new datasets WPOG and CDM. We provide strong baselines based on fine45;tuning models such as BART and GPT45;2 and evaluating zero45;shot performance of models such as ChatGPT and Vicuna. Furthermore we identify an issue of imbalanced utilization of the outline information in the precise outline45;conditioned generation which is ubiquitously observed across fine45;tuned models and zero45;shot inference models. To address this issue we propose an explicit outline utilization control approach and a novel framework that leverages the task duality between summarization and generation. Experimental results show that the proposed approaches effectively alleviate the issue of imbalanced outline utilization and enhance the quality of precise outline45;conditioned text generation for both fine45;tuning and zero45;shot settings.
