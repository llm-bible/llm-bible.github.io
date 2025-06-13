---
layout: publication
title: 'From Beginner To Expert: Modeling Medical Knowledge Into General Llms'
authors: Qiang Li, Xiaoyan Yang, Haowen Wang, Qin Wang, Lei Liu, Junjie Wang, Yang Zhang, Mingyuan Chu, Sen Hu, Yicheng Chen, Yue Shen, Cong Fan, Wangshu Zhang, Teng Xu, Jinjie Gu, Jing Zheng, Guannan Zhang Ant Group
conference: "Arxiv"
year: 2023
bibkey: li2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01040"}
tags: ['Prompting', 'Efficiency and Optimization', 'Applications', 'RAG']
---
Recently, large language model (LLM) based artificial intelligence (AI)
systems have demonstrated remarkable capabilities in natural language
understanding and generation. However, these models face a significant
challenge when it comes to sensitive applications, such as reasoning over
medical knowledge and answering medical questions in a physician-like manner.
Prior studies attempted to overcome this challenge by increasing the model size
(>100B) to learn more general medical knowledge, while there is still room for
improvement in LLMs with smaller-scale model sizes (<100B). In this work, we
start from a pre-trained general LLM model (AntGLM-10B) and fine-tune it from a
medical beginner towards a medical expert (called AntGLM-Med-10B), which
leverages a 3-stage optimization procedure, i.e., general medical knowledge
injection, medical domain instruction tuning, and specific medical task
adaptation. Our contributions are threefold: (1) We specifically investigate
how to adapt a pre-trained general LLM in medical domain, especially for a
specific medical task. (2) We collect and construct large-scale medical
datasets for each stage of the optimization process. These datasets encompass
various data types and tasks, such as question-answering, medical reasoning,
multi-choice questions, and medical conversations. (3) Specifically for
multi-choice questions in the medical domain, we propose a novel
Verification-of-Choice approach for prompting engineering, which significantly
enhances the reasoning ability of LLMs. Remarkably, by combining the above
approaches, our AntGLM-Med-10B model can outperform the most of LLMs on
PubMedQA, including both general and medical LLMs, even when these LLMs have
larger model size.
