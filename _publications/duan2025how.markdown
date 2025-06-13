---
layout: publication
title: 'How Syntax Specialization Emerges In Language Models'
authors: Xufeng Duan, Zhaoqian Yao, Yunhao Zhang, Shaonan Wang, Zhenguang G. Cai
conference: "Arxiv"
year: 2025
bibkey: duan2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19548"}
tags: ['Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism']
---
Large language models (LLMs) have been found to develop surprising internal specializations: Individual neurons, attention heads, and circuits become selectively sensitive to syntactic structure, reflecting patterns observed in the human brain. While this specialization is well-documented, how it emerges during training and what influences its development remains largely unknown.
  In this work, we tap into the black box of specialization by tracking its formation over time. By quantifying internal syntactic consistency across minimal pairs from various syntactic phenomena, we identify a clear developmental trajectory: Syntactic sensitivity emerges gradually, concentrates in specific layers, and exhibits a 'critical period' of rapid internal specialization. This process is consistent across architectures and initialization parameters (e.g., random seeds), and is influenced by model scale and training data. We therefore reveal not only where syntax arises in LLMs but also how some models internalize it during training. To support future research, we will release the code, models, and training checkpoints upon acceptance.
