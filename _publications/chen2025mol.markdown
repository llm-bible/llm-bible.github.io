---
layout: publication
title: 'Mol For Llms: Dual-loss Optimization To Enhance Domain Expertise While Preserving General Capabilities'
authors: Jingxue Chen, Qingkun Tang, Qianchun Lu, Siyuan Fang
conference: "Arxiv"
year: 2025
bibkey: chen2025mol
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12043"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Applications', 'Ethics and Bias', 'Model Architecture', 'Training Techniques']
---
Although large language models (LLMs) perform well in general tasks, domain-specific applications suffer from hallucinations and accuracy limitations. Continual Pre-Training (CPT) approaches encounter two key issues: (1) domain-biased data degrades general language skills, and (2) improper corpus-mixture ratios limit effective adaptation. To address these, we propose a novel framework, Mixture of Losses (MoL), which decouples optimization objectives for domain-specific and general corpora. Specifically, cross-entropy (CE) loss is applied to domain-corpus to ensure knowledge acquisition, while Kullback-Leibler (KL) divergence aligns general-corpus training with the base model's foundational capabilities. This dual-loss architecture preserves universal skills while enhancing domain expertise, avoiding catastrophic forgetting. Empirically, we validate that a 1:1 domain-to-general corpus ratio optimally balances training and overfitting without the need for extensive tuning or resource-intensive experiments. Furthermore, our experiments demonstrate significant performance gains compared to traditional CPT approaches, which often suffer from degradation in general language capabilities; our model achieves 27.9% higher accuracy on the Math-500 benchmark in the non-think reasoning mode, and an impressive 83.3% improvement on the challenging AIME25 subset in the think mode, underscoring the effectiveness of our approach.
