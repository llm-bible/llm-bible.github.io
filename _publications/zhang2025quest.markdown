---
layout: publication
title: 'The Quest For Efficient Reasoning: A Data-centric Benchmark To Cot Distillation'
authors: Ruichen Zhang, Rana Muhammad Shahroz Khan, Zhen Tan, Dawei Li, Song Wang, Tianlong Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025quest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18759"}
  - {name: "Code", url: "https://huggingface.co/datasets/rana-shahroz/DC-COT,"}
  - {name: "Code", url: "https://anonymous.4open.science/r/DC-COT-FF4C/"}
tags: ['Efficiency and Optimization', 'Has Code', 'Distillation', 'Model Architecture']
---
Data-centric distillation, including data augmentation, selection, and mixing, offers a promising path to creating smaller, more efficient student Large Language Models (LLMs) that retain strong reasoning abilities. However, there still lacks a comprehensive benchmark to systematically assess the effect of each distillation approach. This paper introduces DC-CoT, the first data-centric benchmark that investigates data manipulation in chain-of-thought (CoT) distillation from method, model and data perspectives. Utilizing various teacher models (e.g., o4-mini, Gemini-Pro, Claude-3.5) and student architectures (e.g., 3B, 7B parameters), we rigorously evaluate the impact of these data manipulations on student model performance across multiple reasoning datasets, with a focus on in-distribution (IID) and out-of-distribution (OOD) generalization, and cross-domain transfer. Our findings aim to provide actionable insights and establish best practices for optimizing CoT distillation through data-centric techniques, ultimately facilitating the development of more accessible and capable reasoning models. The dataset can be found at https://huggingface.co/datasets/rana-shahroz/DC-COT, while our code is shared in https://anonymous.4open.science/r/DC-COT-FF4C/.
