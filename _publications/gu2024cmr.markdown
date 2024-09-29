---
layout: publication
title: CMR Scaling Law&#58; Predicting Critical Mixture Ratios For Continual Pre-training Of Language Models
authors: Gu Jiawei, Yang Zacc, Ding Chuanghao, Zhao Rui, Tan Fei
conference: "Arxiv"
year: 2024
bibkey: gu2024cmr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17467"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Training Techniques']
---
Large Language Models (LLMs) excel in diverse tasks but often underperform in specialized fields due to limited domain-specific or proprietary corpus. Continual pre-training (CPT) enhances LLM capabilities by imbuing new domain-specific or proprietary knowledge while replaying general corpus to prevent catastrophic forgetting. The data mixture ratio of general corpus and domain-specific corpus however has been chosen heuristically leading to sub-optimal training efficiency in practice. In this context we attempt to re-visit the scaling behavior of LLMs under the hood of CPT and discover a power-law relationship between loss mixture ratio and training tokens scale. We formalize the trade-off between general and domain-specific capabilities leading to a well-defined Critical Mixture Ratio (CMR) of general and domain data. By striking the balance CMR maintains the models general ability and achieves the desired domain transfer ensuring the highest utilization of available resources. Therefore if we value the balance between efficiency and effectiveness CMR can be consider as the optimal mixture ratio.Through extensive experiments we ascertain the predictability of CMR and propose CMR scaling law and have substantiated its generalization. These findings offer practical guidelines for optimizing LLM training in specialized domains ensuring both general and domain-specific performance while efficiently managing training resources.
