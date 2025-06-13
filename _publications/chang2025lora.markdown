---
layout: publication
title: 'Lora-mgpo: Mitigating Double Descent In Low-rank Adaptation Via Momentum-guided Perturbation Optimization'
authors: Yupeng Chang, Chenlu Guo, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2025
bibkey: chang2025lora
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14538'}
  - {name: "Code", url: 'https://github.com/llm172/LoRA-MGPO'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Parameter-efficient fine-tuning (PEFT) methods, such as Low-Rank Adaptation (LoRA), enable efficient adaptation of large language models (LLMs) via low-rank matrix optimization with frozen weights. However, LoRA typically exhibits "double descent" in training loss as rank increases, characterized by a three-phase dynamics: initial convergence, transient divergence, and eventual stabilization. This non-monotonic behavior delays convergence and impairs generalization through unstable gradients and attraction to sharp minima. To address these challenges, we propose LoRA-MGPO, a novel LoRA-based framework incorporating Momentum-Guided Perturbation Optimization (MGPO). First, MGPO eliminates Sharpness-Aware Minimization (SAM)'s dual gradient computations by reusing momentum vectors from optimizer states to guide perturbation directions. This retains SAM's training stability and flat minima preference with maintained efficiency. Second, MGPO incorporates adaptive perturbation normalization, scaling perturbation intensity via exponential moving average (EMA)-smoothed gradient magnitudes. Experiments on natural language understanding and generation benchmarks demonstrate that LoRA-MGPO outperforms LoRA and state-of-the-art PEFT methods. Further analysis confirms its ability to stabilize training and reduce sharp minima attraction, with smoother loss curves and improved convergence behavior. The code is available at https://github.com/llm172/LoRA-MGPO
