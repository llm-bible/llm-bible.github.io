---
layout: publication
title: Towards Building Reliable Language Models With Sparse Mixture-of-experts
authors: Chen Guanjie, Zhao Xinyu, Chen Tianlong, Cheng Yu
conference: "Arxiv"
year: 2024
bibkey: chen2024textttmoe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11353"}
  - {name: "Code", url: "https://github.com/UNITES-Lab/MoE-RBench"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
Mixture-of-Experts (MoE) has gained increasing popularity as a promising framework for scaling up large language models (LLMs). However the reliability assessment of MoE lags behind its surging applications. Moreover when transferred to new domains such as in fine-tuning MoE models sometimes underperform their dense counterparts. Motivated by the research gap and counter-intuitive phenomenon we propose the first comprehensive assessment of SMoE reliability from three aspects safety and hallucination resilience to adversarial attacks and out-of-distribution robustness. Extensive models and datasets are tested to compare the MoE to dense networks from these reliability dimensions. Our empirical observations suggest that with appropriate hyperparameters training recipes and inference techniques we can build the MoE model more reliably than the dense LLM. In particular we find that the robustness of SMoE is sensitive to the basic training settings. We hope that this study can provide deeper insights into how to adapt the pre-trained MoE model to other tasks with higher-generation security quality and stability. Codes are available at https://github.com/UNITES-Lab/MoE-RBench
