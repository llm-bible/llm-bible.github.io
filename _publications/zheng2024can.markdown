---
layout: publication
title: Can LLMs Learn New Concepts Incrementally without Forgetting
authors: Zheng Junhao, Qiu Shengjie, Ma Qianli
conference: "Arxiv"
year: 2024
bibkey: zheng2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08526"}
tags: ['ARXIV', 'Fine Tuning', 'In Context Learning', 'LLM', 'Pretraining Methods']
---
Large Language Models (LLMs) have achieved remarkable success across various tasks yet their ability to learn incrementally without forgetting remains underexplored. Incremental learning (IL) is crucial as it enables models to acquire new knowledge while retaining previously learned information akin to human learning. Existing benchmarks for IL are insufficient due to data leakage issues and the overqualification of LLMs. To address these challenges we introduce Concept-1K a novel dataset comprising 1023 recently emerged concepts across diverse domains. The concepts in Concept-1K are discrete interpretable units of knowledge that allow for fine-grained analysis of learning and forgetting processes. Using Concept-1K as a testbed we aim to answer the question Can LLMs learn new concepts incrementally without forgetting like humans Our investigation reveals that LLMs still suffer from catastrophic forgetting and that LoRA despite fine-tuning fewer parameters may lead to more forgetting on training data. Additionally we explore the roles of in-context learning model scale buffer size and pretraining in IL performance. These findings highlight the strengths and limitations of LLMs in IL scenarios and provide a robust benchmark for future research.
