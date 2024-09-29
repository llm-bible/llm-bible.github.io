---
layout: publication
title: Learnable In45;context Vector For Visual Question Answering
authors: Peng Yingzhe, Hao Chenduo, Yang Xu, Peng Jiawei, Hu Xinting, Geng Xin
conference: "Arxiv"
year: 2024
bibkey: peng2024learnable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13185"}
tags: ['Applications', 'Merging', 'Multimodal Models']
---
As language models continue to scale Large Language Models (LLMs) have exhibited emerging capabilities in In45;Context Learning (ICL) enabling them to solve language tasks by prefixing a few in45;context demonstrations (ICDs) as context. Inspired by these advancements researchers have extended these techniques to develop Large Multimodal Models (LMMs) with ICL capabilities. However applying ICL usually faces two major challenges 1) using more ICDs will largely increase the inference time and 2) the performance is sensitive to the selection of ICDs. These challenges are further exacerbated in LMMs due to the integration of multiple data types and the combinational complexity of multimodal ICDs. Recently to address these challenges some NLP studies introduce non45;learnable In45;Context Vectors (ICVs) which extract useful task information from ICDs into a single vector and then insert it into the LLM to help solve the corresponding task. However although useful in simple NLP tasks these non45;learnable methods fail to handle complex multimodal tasks like Visual Question Answering (VQA). In this study we propose textbf123;Learnable ICV125; (L45;ICV) to distill essential task information from demonstrations improving ICL performance in LMMs. Experiments show that L45;ICV can significantly reduce computational costs while enhancing accuracy in VQA tasks compared to traditional ICL and other non45;learnable ICV methods.
