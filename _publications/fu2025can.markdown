---
layout: publication
title: 'Can An Easy-to-hard Curriculum Make Reasoning Emerge In Small Language Models? Evidence From A Four-stage Curriculum On GPT-2'
authors: Xiang Fu
conference: "Arxiv"
year: 2025
bibkey: fu2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11643"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Attention Mechanism']
---
We demonstrate that a developmentally ordered curriculum markedly improves reasoning transparency and sample-efficiency in small language models (SLMs). Concretely, we train Cognivolve, a 124 M-parameter GPT-2 model, on a four-stage syllabus that ascends from lexical matching to multi-step symbolic inference and then evaluate it without any task-specific fine-tuning. Cognivolve reaches target accuracy in half the optimization steps of a single-phase baseline, activates an order-of-magnitude more gradient-salient reasoning heads, and shifts those heads toward deeper layers, yielding higher-entropy attention that balances local and long-range context. The same curriculum applied out of order or with optimizer resets fails to reproduce these gains, confirming that progression--not extra compute--drives the effect. We also identify open challenges: final-answer success still lags a conventional run by about 30%, and our saliency probe under-detects verbal-knowledge heads in the hardest stage, suggesting directions for mixed-stage fine-tuning and probe expansion.
