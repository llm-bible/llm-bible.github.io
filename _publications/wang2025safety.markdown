---
layout: publication
title: 'Safety Reasoning With Guidelines'
authors: Haoyu Wang, Zeyu Qin, Li Shen, Xueqian Wang, Dacheng Tao, Minhao Cheng
conference: "Arxiv"
year: 2025
bibkey: wang2025safety
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04040'}
tags: ['RAG', 'Security', 'Training Techniques', 'Fine-Tuning', 'Responsible AI']
---
Training safe LLMs remains a critical challenge. The most widely used method, Refusal Training (RT), struggles to generalize against various Out-of-Distribution (OOD) jailbreaking attacks. Although various advanced methods have been proposed to address this issue, we instead question whether OOD attacks inherently surpass the capability of vanilla RT. Evaluations using Best-of-N (BoN) reveal significant safety improvements as N increases, indicating models possess adequate latent safety knowledge but RT fails to consistently elicit it under OOD scenarios. Further domain adaptation analysis reveals that direct RT causes reliance on superficial shortcuts, resulting in non-generalizable representation mappings. Inspired by our findings, we propose training model to perform safety reasoning for each query. Specifically, we synthesize reasoning supervision aligned with specified guidelines that reflect diverse perspectives on safety knowledge. This encourages model to engage in deeper reasoning, explicitly eliciting and utilizing latent safety knowledge for each query. Extensive experiments show that our method significantly improves model generalization against OOD attacks.
