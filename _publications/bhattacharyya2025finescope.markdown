---
layout: publication
title: 'Finescope : Precision Pruning For Domain-specialized Large Language Models Using Sae-guided Self-data Cultivation'
authors: Chaitali Bhattacharyya, Yeseong Kim
conference: "Arxiv"
year: 2025
bibkey: bhattacharyya2025finescope
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00624"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'RAG', 'Distillation', 'Pruning']
---
Training large language models (LLMs) from scratch requires significant
computational resources, driving interest in developing smaller,
domain-specific LLMs that maintain both efficiency and strong task performance.
Medium-sized models such as LLaMA, llama\} have served as starting points for
domain-specific adaptation, but they often suffer from accuracy degradation
when tested on specialized datasets. We introduce FineScope, a framework for
deriving compact, domain-optimized LLMs from larger pretrained models.
FineScope leverages the Sparse Autoencoder (SAE) framework, inspired by its
ability to produce interpretable feature representations, to extract
domain-specific subsets from large datasets. We apply structured pruning with
domain-specific constraints, ensuring that the resulting pruned models retain
essential knowledge for the target domain. To further enhance performance,
these pruned models undergo self-data distillation, leveraging SAE-curated
datasets to restore key domain-specific information lost during pruning.
Extensive experiments and ablation studies demonstrate that FineScope achieves
highly competitive performance, outperforming several large-scale
state-of-the-art LLMs in domain-specific tasks. Additionally, our results show
that FineScope enables pruned models to regain a substantial portion of their
original performance when fine-tuned with SAE-curated datasets. Furthermore,
applying these datasets to fine-tune pretrained LLMs without pruning also
improves their domain-specific accuracy, highlighting the robustness of our
approach. The code will be released.
