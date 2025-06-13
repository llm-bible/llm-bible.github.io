---
layout: publication
title: 'Multi-modal Retrieval Augmented Multi-modal Generation: Datasets, Evaluation Metrics And Strong Baselines'
authors: Zi-ao Ma, Tian Lan, Rong-cheng Tu, Yong Hu, Yu-shi Zhu, Tong Zhang, Heyan Huang, Zhijing Wu, Xian-ling Mao
conference: "Arxiv"
year: 2024
bibkey: ma2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.16365'}
tags: ['Training Techniques', 'RAG', 'Model Architecture', 'GPT']
---
We present a systematic investigation of Multi-modal Retrieval Augmented Multi-modal Generation (M\\(^2\\)RAG), a novel task that enables foundation models to process multi-modal web content and generate multi-modal responses, which exhibits better information density and readability. Despite its potential impact, M\\(^2\\)RAG remains understudied, lacking comprehensive analysis and high-quality data resources. To address this gap, we establish a comprehensive benchmark through a rigorous data curation pipeline, and employ text-modal metrics and multi-modal metrics based on foundation models for evaluation. We further propose several strategies for foundation models to process M\\(^2\\)RAG task effectively and construct a training set by filtering high-quality samples using our designed metrics. Our extensive experiments demonstrate the reliability of our proposed metrics, a landscape of model performance within our designed strategies, and show that our fine-tuned 7B-8B models outperform the GPT-4o model and approach the state-of-the-art OpenAI o3-mini. Additionally, we perform fine-grained analyses across diverse domains and validate the effectiveness of our designs in data curation pipeline. All resources, including codes, datasets, and model weights, will be publicly released.
