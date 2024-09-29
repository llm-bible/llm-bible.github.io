---
layout: publication
title: Infibench Evaluating The Question-answering Capabilities Of Code Large Language Models
authors: Li Linyi, Geng Shijie, Li Zhenwen, He Yibo, Yu Hao, Hua Ziyue, Ning Guanghan, Wang Siwei, Xie Tao, Yang Hongxia
conference: "Arxiv"
year: 2024
bibkey: li2024infibench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07940"}
tags: ['Applications', 'Tools']
---
Large Language Models for code (code LLMs) have witnessed tremendous progress in recent years. With the rapid development of code LLMs many popular evaluation benchmarks such as HumanEval DS-1000 and MBPP have emerged to measure the performance of code LLMs with a particular focus on code generation tasks. However they are insufficient to cover the full range of expected capabilities of code LLMs which span beyond code generation to answering diverse coding-related questions. To fill this gap we propose InfiBench the first large-scale freeform question-answering (QA) benchmark for code to our knowledge comprising 234 carefully selected high-quality Stack Overflow questions that span across 15 programming languages. InfiBench uses four types of model-free automatic metrics to evaluate response correctness where domain experts carefully concretize the criterion for each question. We conduct a systematic evaluation for over 100 latest code LLMs on InfiBench leading to a series of novel and insightful findings. Our detailed analyses showcase potential directions for further advancement of code LLMs. InfiBench is fully open source and continuously expanding to foster more scientific and systematic practices for code LLM evaluation.
