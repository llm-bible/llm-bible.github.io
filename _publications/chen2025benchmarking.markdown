---
layout: publication
title: 'Svgenius: Benchmarking Llms In SVG Understanding, Editing And Generation'
authors: Siqi Chen, Xinyu Dong, Haolei Xu, Xingyu Wu, Fei Tang, Hang Zhang, Yuchen Yan, Linjuan Wu, Wenqi Zhang, Guiyang Hou, Yongliang Shen, Weiming Lu, Yueting Zhuang
conference: "Arxiv"
year: 2025
bibkey: chen2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03139'}
  - {name: "Code", url: 'https://zju-real.github.io/SVGenius'}
tags: ['Has Code', 'RAG', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Large Language Models (LLMs) and Multimodal LLMs have shown promising capabilities for SVG processing, yet existing benchmarks suffer from limited real-world coverage, lack of complexity stratification, and fragmented evaluation paradigms. We introduce SVGenius, a comprehensive benchmark comprising 2,377 queries across three progressive dimensions: understanding, editing, and generation. Built on real-world data from 24 application domains with systematic complexity stratification, SVGenius evaluates models through 8 task categories and 18 metrics. We assess 22 mainstream models spanning different scales, architectures, training paradigms, and accessibility levels. Our analysis reveals that while proprietary models significantly outperform open-source counterparts, all models exhibit systematic performance degradation with increasing complexity, indicating fundamental limitations in current approaches; however, reasoning-enhanced training proves more effective than pure scaling for overcoming these limitations, though style transfer remains the most challenging capability across all model types. SVGenius establishes the first systematic evaluation framework for SVG processing, providing crucial insights for developing more capable vector graphics models and advancing automated graphic design applications. Appendix and supplementary materials (including all data and code) are available at https://zju-real.github.io/SVGenius.
