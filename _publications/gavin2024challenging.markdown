---
layout: publication
title: 'Longins: A Challenging Long-context Instruction-based Exam For Llms'
authors: Gavin Shawn, Zheng Tuney, Liu Jiaheng, Que Quehry, Wang Noah, Yang Jian, Zhang Chenchen, Huang Wenhao, Chen Wenhu, Zhang Ge
conference: "Arxiv"
year: 2024
bibkey: gavin2024challenging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17588"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning']
---
The long-context capabilities of large language models (LLMs) have been a hot
topic in recent years. To evaluate the performance of LLMs in different
scenarios, various assessment benchmarks have emerged. However, as most of
these benchmarks focus on identifying key information to answer questions,
which mainly requires the retrieval ability of LLMs, these benchmarks can
partially represent the reasoning performance of LLMs from large amounts of
information. Meanwhile, although LLMs often claim to have context windows of
32k, 128k, 200k, or even longer, these benchmarks fail to reveal the actual
supported length of these LLMs. To address these issues, we propose the LongIns
benchmark dataset, a challenging long-context instruction-based exam for LLMs,
which is built based on the existing instruction datasets. Specifically, in our
LongIns, we introduce three evaluation settings: Global Instruction & Single
Task (GIST), Local Instruction & Single Task (LIST), and Local Instruction &
Multiple Tasks (LIMT). Based on LongIns, we perform comprehensive evaluations
on existing LLMs and have the following important findings: (1). The
top-performing GPT-4 with 128k context length performs poorly on the evaluation
context window of 16k in our LongIns. (2). For the multi-hop reasoning ability
of many existing LLMs, significant efforts are still needed under short context
windows (less than 4k).
