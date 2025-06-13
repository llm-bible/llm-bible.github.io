---
layout: publication
title: 'LENSLLM: Unveiling Fine-tuning Dynamics For LLM Selection'
authors: Xinyue Zeng, Haohui Wang, Junhong Lin, Jun Wu, Tyler Cody, Dawei Zhou
conference: "Arxiv"
year: 2025
bibkey: zeng2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03793"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
The proliferation of open-sourced Large Language Models (LLMs) and diverse downstream tasks necessitates efficient model selection, given the impracticality of fine-tuning all candidates due to computational constraints. Despite the recent advances in LLM selection, a fundamental research question largely remains nascent: how can we model the dynamic behaviors of LLMs during fine-tuning, thereby enhancing our understanding of their generalization performance across diverse downstream tasks? In this work, we propose a novel theoretical framework that provides a proper lens to assess the generalization capabilities of LLMs, thereby enabling accurate and efficient LLM selection for downstream applications. In particular, we first derive a PAC-Bayesian Generalization Bound that unveils fine-tuning dynamics of LLMs and then introduce LENSLLM, a Neural Tangent Kernel (NTK)-based Rectified Scaling Model that enables accurate performance predictions across diverse tasks while maintaining computational efficiency. Extensive empirical results on 3 large-scale benchmarks demonstrate that our model achieves up to 91.1% accuracy and reduces up to 88.5% computational cost in LLM selection, outperforming 5 state-of-the-art methods. We open-source our proposed LENSLLM model and corresponding results at LensLLM.io.
