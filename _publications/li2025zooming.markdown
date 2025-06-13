---
layout: publication
title: 'Zooming From Context To Cue: Hierarchical Preference Optimization For Multi-image Mllms'
authors: Xudong Li, Mengdan Zhang, Peixian Chen, Xiawu Zheng, Yan Zhang, Jingyuan Zheng, Yunhang Shen, Ke Li, Chaoyou Fu, Xing Sun, Rongrong Ji
conference: "Arxiv"
year: 2025
bibkey: li2025zooming
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.22396'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Prompting', 'Multimodal Models', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Multi-modal Large Language Models (MLLMs) excel at single-image tasks but struggle with multi-image understanding due to cross-modal misalignment, leading to hallucinations (context omission, conflation, and misinterpretation). Existing methods using Direct Preference Optimization (DPO) constrain optimization to a solitary image reference within the input sequence, neglecting holistic context modeling. We propose Context-to-Cue Direct Preference Optimization (CcDPO), a multi-level preference optimization framework that enhances per-image perception in multi-image settings by zooming into visual clues -- from sequential context to local details. It features: (i) Context-Level Optimization : Re-evaluates cognitive biases underlying MLLMs' multi-image context comprehension and integrates a spectrum of low-cost global sequence preferences for bias mitigation. (ii) Needle-Level Optimization : Directs attention to fine-grained visual details through region-targeted visual prompts and multimodal preference supervision. To support scalable optimization, we also construct MultiScope-42k, an automatically generated dataset with high-quality multi-level preference pairs. Experiments show that CcDPO significantly reduces hallucinations and yields consistent performance gains across general single- and multi-image tasks.
