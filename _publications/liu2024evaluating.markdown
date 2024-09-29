---
layout: publication
title: Mibench Evaluating Multimodal Large Language Models Over Multiple Images
authors: Liu Haowei, Zhang Xi, Xu Haiyang, Shi Yaya, Jiang Chaoya, Yan Ming, Zhang Ji, Huang Fei, Yuan Chunfeng, Li Bing, Hu Weiming
conference: "Arxiv"
year: 2024
bibkey: liu2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15272"}
tags: ['Multimodal Models']
---
Built on the power of LLMs numerous multimodal large language models (MLLMs) have recently achieved remarkable performance on various vision45;language tasks across multiple benchmarks. However most existing MLLMs and benchmarks primarily focus on single45;image input scenarios leaving the performance of MLLMs when handling realistic multiple images remain underexplored. Although a few benchmarks consider multiple images their evaluation dimensions and samples are very limited. Therefore in this paper we propose a new benchmark MIBench to comprehensively evaluate fine45;grained abilities of MLLMs in multi45;image scenarios. Specifically MIBench categorizes the multi45;image abilities into three scenarios multi45;image instruction (MII) multimodal knowledge45;seeking (MKS) and multimodal in45;context learning (MIC) and constructs 13 tasks with a total of 13K annotated samples. During data construction for MII and MKS we extract correct options from manual annotations and create challenging distractors to obtain multiple45;choice questions. For MIC to enable an in45;depth evaluation we set four sub45;tasks and transform the original datasets into in45;context learning formats. We evaluate several open45;source MLLMs and close45;source MLLMs on the proposed MIBench. The results reveal that although current models excel in single45;image tasks they exhibit significant shortcomings when faced with multi45;image inputs such as confused fine45;grained perception limited multi45;image reasoning and unstable in45;context learning. The annotated data in MIBench is available at https://huggingface.co/datasets/StarBottle/MIBench.
