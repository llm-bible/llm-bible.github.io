---
layout: publication
title: 'Moh: Multi-head Attention As Mixture-of-head Attention'
authors: Peng Jin, Bo Zhu, Li Yuan, Shuicheng Yan
conference: "Arxiv"
year: 2024
bibkey: jin2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11842"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods']
---
In this work, we upgrade the multi-head attention mechanism, the core of the
Transformer model, to improve efficiency while maintaining or surpassing the
previous accuracy level. We show that multi-head attention can be expressed in
the summation form. Drawing on the insight that not all attention heads hold
equal significance, we propose Mixture-of-Head attention (MoH), a new
architecture that treats attention heads as experts in the Mixture-of-Experts
(MoE) mechanism. MoH has two significant advantages: First, MoH enables each
token to select the appropriate attention heads, enhancing inference efficiency
without compromising accuracy or increasing the number of parameters. Second,
MoH replaces the standard summation in multi-head attention with a weighted
summation, introducing flexibility to the attention mechanism and unlocking
extra performance potential. Extensive experiments on ViT, DiT, and LLMs
demonstrate that MoH outperforms multi-head attention by using only 50%-90% of
the attention heads. Moreover, we demonstrate that pre-trained multi-head
attention models, such as LLaMA3-8B, can be further continue-tuned into our MoH
models. Notably, MoH-LLaMA3-8B achieves an average accuracy of 64.0% across 14
benchmarks, outperforming LLaMA3-8B by 2.4% by utilizing only 75% of the
attention heads. We believe the proposed MoH is a promising alternative to
multi-head attention and provides a strong foundation for developing advanced
and efficient attention-based models.
