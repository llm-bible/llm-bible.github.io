---
layout: publication
title: "Low-resource Cross-lingual Summarization Through Few-shot Learning With Large Language Models"
authors: Park Gyutae, Hwang Seojin, Lee Hwanhee
conference: "Arxiv"
year: 2024
bibkey: park2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04630"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Cross-lingual summarization (XLS) aims to generate a summary in a target language different from the source language document. While large language models (LLMs) have shown promising zero-shot XLS performance their few-shot capabilities on this task remain unexplored especially for low-resource languages with limited parallel data. In this paper we investigate the few-shot XLS performance of various models including Mistral-7B-Instruct-v0.2 GPT-3.5 and GPT-4. Our experiments demonstrate that few-shot learning significantly improves the XLS performance of LLMs particularly GPT-3.5 and GPT-4 in low-resource settings. However the open-source model Mistral-7B-Instruct-v0.2 struggles to adapt effectively to the XLS task with limited examples. Our findings highlight the potential of few-shot learning for improving XLS performance and the need for further research in designing LLM architectures and pre-training objectives tailored for this task. We provide a future work direction to explore more effective few-shot learning strategies and to investigate the transfer learning capabilities of LLMs for cross-lingual summarization.
