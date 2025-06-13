---
layout: publication
title: 'Reflectevo: Improving Meta Introspection Of Small Llms By Learning Self-reflection'
authors: Jiaqi Li, Xinyi Dong, Yang Liu, Zhizhuo Yang, Quansen Wang, Xiaobo Wang, Songchun Zhu, Zixia Jia, Zilong Zheng
conference: "Arxiv"
year: 2025
bibkey: li2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16475'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
We present a novel pipeline, ReflectEvo, to demonstrate that small language models (SLMs) can enhance meta introspection through reflection learning. This process iteratively generates self-reflection for self-training, fostering a continuous and self-evolving process. Leveraging this pipeline, we construct ReflectEvo-460k, a large-scale, comprehensive, self-generated reflection dataset with broadened instructions and diverse multi-domain tasks. Building upon this dataset, we demonstrate the effectiveness of reflection learning to improve SLMs' reasoning abilities using SFT and DPO with remarkable performance, substantially boosting Llama-3 from 52.4% to 71.2% and Mistral from 44.4% to 71.1%. It validates that ReflectEvo can rival or even surpass the reasoning capability of the three prominent open-sourced models on BIG-bench without distillation from superior models or fine-grained human annotation. We further conduct a deeper analysis of the high quality of self-generated reflections and their impact on error localization and correction. Our work highlights the potential of continuously enhancing the reasoning performance of SLMs through iterative reflection learning in the long run.
