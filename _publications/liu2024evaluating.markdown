---
layout: publication
title: 'Mibench: Evaluating Multimodal Large Language Models Over Multiple Images'
authors: Liu Haowei, Zhang Xi, Xu Haiyang, Shi Yaya, Jiang Chaoya, Yan Ming, Zhang Ji, Huang Fei, Yuan Chunfeng, Li Bing, Hu Weiming
conference: "Arxiv"
year: 2024
bibkey: liu2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15272"}
tags: ['In Context Learning', 'Multimodal Models', 'Prompting']
---
'Built on the power of LLMs, numerous multimodal large language models (MLLMs) have recently achieved remarkable performance on various vision-language tasks across multiple benchmarks. However, most existing MLLMs and benchmarks primarily focus on single-image input scenarios, leaving the performance of MLLMs when handling realistic multiple images remain underexplored. Although a few benchmarks consider multiple images, their evaluation dimensions and samples are very limited. Therefore, in this paper, we propose a new benchmark MIBench, to comprehensively evaluate fine-grained abilities of MLLMs in multi-image scenarios. Specifically, MIBench categorizes the multi-image abilities into three scenarios: multi-image instruction (MII), multimodal knowledge-seeking (MKS) and multimodal in-context learning (MIC), and constructs 13 tasks with a total of 13K annotated samples. During data construction, for MII and MKS, we extract correct options from manual annotations and create challenging distractors to obtain multiple-choice questions. For MIC, to enable an in-depth evaluation, we set four sub-tasks and transform the original datasets into in-context learning formats. We evaluate several open-source MLLMs and close-source MLLMs on the proposed MIBench. The results reveal that although current models excel in single-image tasks, they exhibit significant shortcomings when faced with multi-image inputs, such as confused fine-grained perception, limited multi-image reasoning, and unstable in-context learning. The annotated data in MIBench is available at https://huggingface.co/datasets/StarBottle/MIBench.'
