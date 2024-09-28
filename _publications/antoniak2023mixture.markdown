---
layout: publication
title: Mixture of Tokens Efficient LLMs through Cross-Example Aggregation
authors: Antoniak Szymon, Jaszczur Sebastian, Krutul Michał, Pióro Maciej, Krajewski Jakub, Ludziejewski Jan, Odrzygóźdź Tomasz, Cygan Marek
conference: "Arxiv"
year: 2023
bibkey: antoniak2023mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15961"}
tags: ['ARXIV', 'Applications', 'Transformer']
---
Despite the promise of Mixture of Experts (MoE) models in increasing parameter counts of Transformer models while maintaining training and inference costs their application carries notable drawbacks. The key strategy of these models is to for each processed token activate at most a few experts - subsets of an extensive feed-forward layer. But this approach is not without its challenges. The operation of matching experts and tokens is discrete which makes MoE models prone to issues like training instability and uneven expert utilization. Existing techniques designed to address these concerns such as auxiliary losses or balance-aware matching result either in lower model performance or are more difficult to train. In response to these issues we propose Mixture of Tokens a fully-differentiable model that retains the benefits of MoE architectures while avoiding the aforementioned difficulties. Rather than routing tokens to experts this approach mixes tokens from different examples prior to feeding them to experts enabling the model to learn from all token-expert combinations. Importantly this mixing can be disabled to avoid mixing of different sequences during inference. Crucially this method is fully compatible with both masked and causal Large Language Model training and inference.
