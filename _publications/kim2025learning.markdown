---
layout: publication
title: 'Learning To Insert [PAUSE] Tokens For Better Reasoning'
authors: Eunki Kim, Sangryul Kim, James Thorne
conference: "Arxiv"
year: 2025
bibkey: kim2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03616"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
To enhance reasoning capabilities, previous works have explored incorporating special-purpose tokens into the training process. These strategies strengthen the learning mechanism of transformer-based large language models (LLMs). Building on prior research, in which inserting dummy tokens consecutively just before reasoning steps can enhance effectiveness, we introduce a novel approach termed Dynamic Inserting Tokens Training (DIT). Our method identifies positions within sequences where model confidence is lowest according to token log-likelihood. Strategically inserting [PAUSE] tokens on these positions bolsters the model's predictive capabilities for subsequent tokens. Experimental results across diverse datasets and models, from the 2.7B model to the 8B model, demonstrate that DIT consistently outperforms traditional fine-tuning and previous token insertion methods. With this simple yet effective method, we achieve accuracy gains of up to 4.7%p on GSM8K, 3.23%p on AQUA-RAT, and pass@1 improvements of up to 3.4%p on MBPP datasets. Our work shows a model-based, dynamic approach rather than a heuristic one, thereby broadening the scope of research in reasoning.
