---
layout: publication
title: A Token45;level Reference45;free Hallucination Detection Benchmark For Free45;form Text Generation
authors: Liu Tianyu, Zhang Yizhe, Brockett Chris, Mao Yi, Sui Zhifang, Chen Weizhu, Dolan Bill
conference: "Arxiv"
year: 2021
bibkey: liu2021token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.08704"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture']
---
Large pretrained generative models like GPT45;3 often suffer from hallucinating non45;existent or incorrect content which undermines their potential merits in real applications. Existing work usually attempts to detect these hallucinations based on a corresponding oracle reference at a sentence or document level. However ground45;truth references may not be readily available for many free45;form text generation applications and sentence45; or document45;level detection may fail to provide the fine45;grained signals that would prevent fallacious content in real time. As a first step to addressing these issues we propose a novel token45;level reference45;free hallucination detection task and an associated annotated dataset named HaDes (HAllucination DEtection dataSet). To create this dataset we first perturb a large number of text segments extracted from English language Wikipedia and then verify these with crowd45;sourced annotations. To mitigate label imbalance during annotation we utilize an iterative model45;in45;loop strategy. We conduct comprehensive data analyses and create multiple baseline models.
