---
layout: publication
title: 'Attention Calibration For Transformer-based Sequential Recommendation'
authors: Peilin Zhou, Qichen Ye, Yueqi Xie, Jingqi Gao, Shoujin Wang, Jae Boum Kim, Chenyu You, Sunghun Kim
conference: "Arxiv"
year: 2023
bibkey: zhou2023attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.09419'}
  - {name: "Code", url: 'https://github.com/AIM-SE/AC-TSR'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based sequential recommendation (SR) has been booming in recent
years, with the self-attention mechanism as its key component. Self-attention
has been widely believed to be able to effectively select those informative and
relevant items from a sequence of interacted items for next-item prediction via
learning larger attention weights for these items. However, this may not always
be true in reality. Our empirical analysis of some representative
Transformer-based SR models reveals that it is not uncommon for large attention
weights to be assigned to less relevant items, which can result in inaccurate
recommendations. Through further in-depth analysis, we find two factors that
may contribute to such inaccurate assignment of attention weights: sub-optimal
position encoding and noisy input. To this end, in this paper, we aim to
address this significant yet challenging gap in existing works. To be specific,
we propose a simple yet effective framework called Attention Calibration for
Transformer-based Sequential Recommendation (AC-TSR). In AC-TSR, a novel
spatial calibrator and adversarial calibrator are designed respectively to
directly calibrates those incorrectly assigned attention weights. The former is
devised to explicitly capture the spatial relationships (i.e., order and
distance) among items for more precise calculation of attention weights. The
latter aims to redistribute the attention weights based on each item's
contribution to the next-item prediction. AC-TSR is readily adaptable and can
be seamlessly integrated into various existing transformer-based SR models.
Extensive experimental results on four benchmark real-world datasets
demonstrate the superiority of our proposed ACTSR via significant
recommendation performance enhancements. The source code is available at
https://github.com/AIM-SE/AC-TSR.
