---
layout: publication
title: 'Quantization Error Propagation: Revisiting Layer-wise Post-training Quantization'
authors: Yamato Arai, Yuma Ichikawa
conference: "Arxiv"
year: 2025
bibkey: arai2025quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09629"}
tags: ['Tools', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Quantization']
---
Layer-wise PTQ is a promising technique for compressing large language models (LLMs), due to its simplicity and effectiveness without requiring retraining. However, recent progress in this area is saturating, underscoring the need to revisit its core limitations and explore further improvements. We address this challenge by identifying a key limitation of existing layer-wise PTQ methods: the growth of quantization errors across layers significantly degrades performance, particularly in low-bit regimes. To address this fundamental issue, we propose Quantization Error Propagation (QEP), a general, lightweight, and scalable framework that enhances layer-wise PTQ by explicitly propagating quantization errors and compensating for accumulated errors. QEP also offers a tunable propagation mechanism that prevents overfitting and controls computational overhead, enabling the framework to adapt to various architectures and resource budgets. Extensive experiments on several LLMs demonstrate that QEP-enhanced layer-wise PTQ achieves substantially higher accuracy than existing methods. Notably, the gains are most pronounced in the extremely low-bit quantization regime.
