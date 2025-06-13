---
layout: publication
title: 'Soaesv2-7b/72b: Full-pipeline Optimization For State-owned Enterprise Llms Via Continual Pre-training, Domain-progressive SFT And Distillation-enhanced Speculative Decoding'
authors: Jingyang Deng, Ran Chen, Jo-ku Cheng, Jinwen Ma
conference: "Arxiv"
year: 2025
bibkey: deng2025full
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04723"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
This study addresses key challenges in developing domain-specific large
language models (LLMs) for Chinese state-owned assets and enterprises (SOAEs),
where current approaches face three limitations: 1) constrained model capacity
that limits knowledge integration and cross-task adaptability; 2) excessive
reliance on domain-specific supervised fine-tuning (SFT) data, which neglects
the broader applicability of general language patterns; and 3) inefficient
inference acceleration for large models processing long contexts. In this work,
we propose SOAEsV2-7B/72B, a specialized LLM series developed via a three-phase
framework: 1) continual pre-training integrates domain knowledge while
retaining base capabilities; 2) domain-progressive SFT employs curriculum-based
learning strategy, transitioning from weakly relevant conversational data to
expert-annotated SOAEs datasets to optimize domain-specific tasks; 3)
distillation-enhanced speculative decoding accelerates inference via logit
distillation between 72B target and 7B draft models, achieving
1.39-1.52\\(\times\\) speedup without quality loss. Experimental results
demonstrate that our domain-specific pre-training phase maintains 99.8% of
original general language capabilities while significantly improving domain
performance, resulting in a 1.08\\(\times\\) improvement in Rouge-1 score and a
1.17\\(\times\\) enhancement in BLEU-4 score. Ablation studies further show that
domain-progressive SFT outperforms single-stage training, achieving
1.02\\(\times\\) improvement in Rouge-1 and 1.06\\(\times\\) in BLEU-4. Our work
introduces a comprehensive, full-pipeline approach for optimizing SOAEs LLMs,
bridging the gap between general language capabilities and domain-specific
expertise.
