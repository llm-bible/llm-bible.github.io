---
layout: publication
title: 'Mutual Enhancement Of Large And Small Language Models With Cross-silo Knowledge Transfer'
authors: Yongheng Deng, Ziqing Qiao, Ju Ren, Yang Liu, Yaoxue Zhang
conference: "Arxiv"
year: 2023
bibkey: deng2023mutual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.05842'}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
While large language models (LLMs) are empowered with broad knowledge, their
task-specific performance is often suboptimal. It necessitates fine-tuning LLMs
with task-specific data, but such data may be inaccessible due to privacy
concerns. In this paper, we propose a novel approach to enhance LLMs with
smaller language models (SLMs) that are trained on clients using their private
task-specific data. To enable mutual enhancement between LLMs and SLMs, we
propose CrossLM, where the SLMs promote the LLM to generate task-specific
high-quality data, and both the LLM and SLMs are enhanced with the generated
data. We evaluate CrossLM using publicly accessible language models across a
range of benchmark tasks. The results demonstrate that CrossLM significantly
enhances the task-specific performance of SLMs on clients and the LLM on the
cloud server simultaneously while preserving the LLM's generalization
capability.
