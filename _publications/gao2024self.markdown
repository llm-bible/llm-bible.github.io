---
layout: publication
title: 'Sprec: Self-play To Debias Llm-based Recommendation'
authors: Chongming Gao, Ruijun Chen, Shuai Yuan, Kexin Huang, Yuanqing Yu, Xiangnan He
conference: "Arxiv"
year: 2024
bibkey: gao2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09243"}
  - {name: "Code", url: "https://github.com/RegionCh/SPRec"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fairness', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
Large language models (LLMs) have attracted significant attention in
recommendation systems. Current work primarily applies supervised fine-tuning
(SFT) to adapt the model for recommendation tasks. However, SFT on positive
examples only limits the model's ability to align with user preference. To
address this, researchers recently introduced Direct Preference Optimization
(DPO), which explicitly aligns LLMs with user preferences using offline
preference ranking data. However, we found that DPO inherently biases the model
towards a few items, exacerbating the filter bubble issue and ultimately
degrading user experience.
  In this paper, we propose SPRec, a novel self-play framework designed to
mitigate over-recommendation and improve fairness without requiring additional
data or manual intervention. In each self-play iteration, the model undergoes
an SFT step followed by a DPO step, treating offline interaction data as
positive samples and the predicted outputs from the previous iteration as
negative samples. This effectively re-weights the DPO loss function using the
model's logits, adaptively suppressing biased items. Extensive experiments on
multiple real-world datasets demonstrate SPRec's effectiveness in enhancing
recommendation accuracy and fairness. The implementation is available via
https://github.com/RegionCh/SPRec
