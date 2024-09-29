---
layout: publication
title: Mementos A Comprehensive Benchmark For Multimodal Large Language Model Reasoning Over Image Sequences
authors: Wang Xiyao, Zhou Yuhang, Liu Xiaoyu, Lu Hongjin, Xu Yuancheng, He Feihong, Yoon Jaehong, Lu Taixi, Bertasius Gedas, Bansal Mohit, Yao Huaxiu, Huang Furong
conference: "Arxiv"
year: 2024
bibkey: wang2024mementos
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10529"}
  - {name: "Code", url: "https://github.com/umd-huang-lab/Mementos"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal Large Language Models (MLLMs) have demonstrated proficiency in handling a variety of visual-language tasks. However current MLLM benchmarks are predominantly designed to evaluate reasoning based on static information about a single image and the ability of modern MLLMs to extrapolate from image sequences which is essential for understanding our ever-changing world has been less investigated. To address this challenge this paper introduces Mementos a new benchmark designed to assess MLLMs sequential image reasoning abilities. Mementos features 4761 diverse image sequences with varying lengths. We also employ a GPT-4 assisted method to evaluate MLLM reasoning performance. Through a careful evaluation of nine recent MLLMs on Mementos including GPT-4V and Gemini we find that they struggle to accurately describe dynamic information about given image sequences often leading to hallucinations/misrepresentations of objects and their corresponding behaviors. Our quantitative analysis and case studies identify three key factors impacting MLLMs sequential image reasoning the correlation between object and behavioral hallucinations the influence of cooccurring behaviors and the compounding impact of behavioral hallucinations. Our dataset is available at https://github.com/umd-huang-lab/Mementos.
