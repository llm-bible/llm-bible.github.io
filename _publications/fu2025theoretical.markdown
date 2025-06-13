---
layout: publication
title: 'A Theoretical Perspective: How To Prevent Model Collapse In Self-consuming Training Loops'
authors: Shi Fu, Yingjie Wang, Yuzhu Chen, Xinmei Tian, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: fu2025theoretical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18865"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
High-quality data is essential for training large generative models, yet the
vast reservoir of real data available online has become nearly depleted.
Consequently, models increasingly generate their own data for further training,
forming Self-consuming Training Loops (STLs). However, the empirical results
have been strikingly inconsistent: some models degrade or even collapse, while
others successfully avoid these failures, leaving a significant gap in
theoretical understanding to explain this discrepancy. This paper introduces
the intriguing notion of recursive stability and presents the first theoretical
generalization analysis, revealing how both model architecture and the
proportion between real and synthetic data influence the success of STLs. We
further extend this analysis to transformers in in-context learning, showing
that even a constant-sized proportion of real data ensures convergence, while
also providing insights into optimal synthetic data sizing.
