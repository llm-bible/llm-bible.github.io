---
layout: publication
title: 'Exploring Concept Depth: How Large Language Models Acquire Knowledge At Different Layers?'
authors: Jin Mingyu, Yu Qinkai, Huang Jingyuan, Zeng Qingcheng, Wang Zhenting, Hua Wenyue, Zhao Haiyan, Mei Kai, Meng Yanda, Ding Kaize, Yang Fan, Du Mengnan, Zhang Yongfeng
conference: "Arxiv"
year: 2024
bibkey: jin2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07066"}
  - {name: "Code", url: "https://github.com/Luckfort/CD"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning']
---
'Large language models (LLMs) have shown remarkable performances across a wide range of tasks. However, the mechanisms by which these models encode tasks of varying complexities remain poorly understood. In this paper, we explore the hypothesis that LLMs process concepts of varying complexities in different layers, introducing the idea of Concept Depth to suggest that more complex concepts are typically acquired in deeper layers. Specifically, we categorize concepts based on their level of abstraction, defining them in the order of increasing complexity within factual, emotional, and inferential tasks. We conduct extensive probing experiments using layer-wise representations across various LLM families (Gemma, LLaMA, QWen) on various datasets spanning the three domains of tasks. Our findings reveal that models could efficiently conduct probing for simpler tasks in shallow layers, and more complex tasks typically necessitate deeper layers for accurate understanding. Additionally, we examine how external factors, such as adding noise to the input and quantizing the model weights, might affect layer-wise representations. Our findings suggest that these factors can impede the development of a conceptual understanding of LLMs until deeper layers are explored. We hope that our proposed concept and experimental insights will enhance the understanding of the mechanisms underlying LLMs. Our codes are available at https://github.com/Luckfort/CD.'
