---
layout: publication
title: Can Llms Learn New Concepts Incrementally Without Forgetting
authors: Zheng Junhao, Qiu Shengjie, Ma Qianli
conference: "Arxiv"
year: 2024
bibkey: zheng2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08526"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLMs) have achieved remarkable success across various tasks yet their ability to learn incrementally without forgetting remains underexplored. Incremental learning (IL) is crucial as it enables models to acquire new knowledge while retaining previously learned information akin to human learning. Existing benchmarks for IL are insufficient due to data leakage issues and the overqualification of LLMs. To address these challenges we introduce Concept45;1K a novel dataset comprising 1023 recently emerged concepts across diverse domains. The concepts in Concept45;1K are discrete interpretable units of knowledge that allow for fine45;grained analysis of learning and forgetting processes. Using Concept45;1K as a testbed we aim to answer the question Can LLMs learn new concepts incrementally without forgetting like humans Our investigation reveals that LLMs still suffer from catastrophic forgetting and that LoRA despite fine45;tuning fewer parameters may lead to more forgetting on training data. Additionally we explore the roles of in45;context learning model scale buffer size and pretraining in IL performance. These findings highlight the strengths and limitations of LLMs in IL scenarios and provide a robust benchmark for future research.
