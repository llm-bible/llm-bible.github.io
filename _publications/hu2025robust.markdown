---
layout: publication
title: 'DONOD: Robust And Generalizable Instruction Fine-tuning For Llms Via Model-intrinsic Dataset Pruning'
authors: Jucheng Hu, Surong Yang, Dongzhan Zhou, Lijun Wu
conference: "Arxiv"
year: 2025
bibkey: hu2025robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14810"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Pruning', 'Pretraining Methods', 'Fine-Tuning']
---
Ad-hoc instruction fine-tuning of large language models (LLMs) is widely
adopted for domain-specific adaptation. While domain-specific supervised
fine-tuning (SFT) is effective and efficient, it often weakens cross-domain
generalization and struggles with noisy training data. To address these
challenges, we propose DONOD, a lightweight model-intrinsic data pruning
method. Our approach evaluates data using two model-parameter-based metrics:
Delta of Norm (DON), which captures the cumulative influence on model weights,
and Norm of Delta (NOD), which quantifies weight instability. Moreover, by
employing the Technique for Order of Preference by Similarity to Ideal Solution
(TOPSIS) algorithm, we effectively filter noisy, unlearnable, and
generalization-harming samples without relying on auxiliary models during the
SFT process. Experiments on mathematical tasks demonstrate that data selected
by DONOD achieve superior fine-tuning efficiency and improved robustness
against noisy data. By filtering out 70% of the full dataset, we improve
target-domain accuracy by 14.90% and cross-domain accuracy by 5.67%. Meanwhile,
our selected data present superior cross-architecture generalization. Data
pruned by smaller models (e.g., Llama 3.1-8B) generalize effectively on larger
models (e.g., Llama 2-13B). Compared to existing related methodologies, DONOD
demonstrates comparable or superior performance while remaining
dataset-agnostic, enabling broader applicability.
