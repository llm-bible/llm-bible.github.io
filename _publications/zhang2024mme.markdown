---
layout: publication
title: MME-RealWorld Could Your multivocal lam Challenge High-Resolution Real-World Scenarios that are Difficult for Humans
authors: Zhang Yi-fan, Zhang Huanyu, Tian Haochen, Fu Chaoyou, Zhang Shuangqing, Wu Junfei, Li Feng, Wang Kun, Wen Qingsong, Zhang Zhang, Wang Liang, Jin Rong, Tan Tieniu
conference: "Arxiv"
year: 2024
bibkey: zhang2024mme
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13257"}
  - {name: "Code", url: "https://mme-realworld.github.io/"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Comprehensive evaluation of Multimodal Large Language Models (MLLMs) has recently garnered widespread attention in the research community. However we observe that existing benchmarks present several common barriers that make it difficult to measure the significant challenges that models face in the real world including 1) small data scale leads to a large performance variance; 2) reliance on model-based annotations results in restricted data quality; 3) insufficient task difficulty especially caused by the limited image resolution. To tackle these issues we introduce MME-RealWorld. Specifically we collect more than 300K images from public datasets and the Internet filtering 13366 high-quality images for annotation. This involves the efforts of professional 25 annotators and 7 experts in MLLMs contributing to 29429 question-answer pairs that cover 43 subtasks across 5 real-world scenarios extremely challenging even for humans. As far as we know MME-RealWorld is the largest manually annotated benchmark to date featuring the highest resolution and a targeted focus on real-world applications. We further conduct a thorough evaluation involving 28 prominent MLLMs such as GPT-4o Gemini 1.5 Pro and Claude 3.5 Sonnet. Our results show that even the most advanced models struggle with our benchmarks where none of them reach 60 accuracy. The challenges of perceiving high-resolution images and understanding complex real-world scenarios remain urgent issues to be addressed. The data and evaluation code are released at https://mme-realworld.github.io/ .
