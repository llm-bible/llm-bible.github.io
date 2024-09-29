---
layout: publication
title: M4U&#58; Evaluating Multilingual Understanding And Reasoning For Large Multimodal Models
authors: Wang Hongyu, Xu Jiayu, Xie Senwei, Wang Ruiping, Li Jialin, Xie Zhaojie, Zhang Bin, Xiong Chuyan, Chen Xilin
conference: "Arxiv"
year: 2024
bibkey: wang2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15638"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools']
---
Multilingual multimodal reasoning is a core component in achieving human-level intelligence. However most existing benchmarks for multilingual multimodal reasoning struggle to differentiate between models of varying performance; even language models without visual capabilities can easily achieve high scores. This leaves a comprehensive evaluation of leading multilingual multimodal models largely unexplored. In this work we introduce M4U a novel and challenging benchmark for assessing the capability of multi-discipline multilingual multimodal understanding and reasoning. M4U contains 8931 samples covering 64 disciplines across 16 subfields in Science Engineering and Healthcare in Chinese English and German. Using M4U we conduct extensive evaluations of 21 leading Large Multimodal Models (LMMs) and Large Language Models (LLMs) with external tools. The evaluation results show that the state-of-the-art model GPT-4o achieves only 47.637; average accuracy on M4U. Additionally we observe that the leading LMMs exhibit significant language preferences. Our in-depth analysis indicates that leading LMMs including GPT-4o suffer performance degradation when prompted with cross-lingual multimodal questions such as images with key textual information in Chinese while the question is in German. We believe that M4U can serve as a crucial tool for systematically evaluating LMMs based on their multilingual multimodal reasoning capabilities and monitoring their development. The homepage codes and data are public available.
