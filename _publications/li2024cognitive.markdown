---
layout: publication
title: Cognitive Visual45;language Mapper Advancing Multimodal Comprehension With Enhanced Visual Knowledge Alignment
authors: Li Yunxin, Chen Xinyu, Hu Baotian, Shi Haoyuan, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: li2024cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13561"}
  - {name: "Code", url: "https://github.com/HITsz&#45;TMG/Cognitive&#45;Visual&#45;Language&#45;Mapper"}
tags: ['Applications', 'Has Code', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Evaluating and Rethinking the current landscape of Large Multimodal Models (LMMs) we observe that widely45;used visual45;language projection approaches (e.g. Q45;former or MLP) focus on the alignment of image45;text descriptions yet ignore the visual knowledge45;dimension alignment i.e. connecting visuals to their relevant knowledge. Visual knowledge plays a significant role in analyzing inferring and interpreting information from visuals helping improve the accuracy of answers to knowledge45;based visual questions. In this paper we mainly explore improving LMMs with visual45;language knowledge alignment especially aimed at challenging knowledge45;based visual question answering (VQA). To this end we present a Cognitive Visual45;Language Mapper (CVLM) which contains a pretrained Visual Knowledge Aligner (VKA) and a Fine45;grained Knowledge Adapter (FKA) used in the multimodal instruction tuning stage. Specifically we design the VKA based on the interaction between a small language model and a visual encoder training it on collected image45;knowledge pairs to achieve visual knowledge acquisition and projection. FKA is employed to distill the fine45;grained visual knowledge of an image and inject it into Large Language Models (LLMs). We conduct extensive experiments on knowledge45;based VQA benchmarks and experimental results show that CVLM significantly improves the performance of LMMs on knowledge45;based VQA (average gain by 5.037;). Ablation studies also verify the effectiveness of VKA and FKA respectively. The codes are available at https://github.com/HITsz&#45;TMG/Cognitive&#45;Visual&#45;Language&#45;Mapper
