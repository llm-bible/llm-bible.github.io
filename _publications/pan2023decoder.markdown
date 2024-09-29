---
layout: publication
title: Stelocoder A Decoder45;only LLM For Multi45;language To Python Code Translation
authors: Pan Jialing, Sadé Adrien, Kim Jin, Soriano Eric, Sole Guillem, Flamant Sylvain
conference: "Arxiv"
year: 2023
bibkey: pan2023decoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15539"}
  - {name: "Code", url: "https://github.com/sade&#45;adrien/SteloCoder"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Model Architecture', 'RAG', 'Training Techniques']
---
With the recent focus on Large Language Models (LLMs) both StarCoder (Li et al. 2023) and Code Llama (Roziere et al. 2023) have demonstrated remarkable performance in code generation. However there is still a need for improvement in code translation functionality with efficient training techniques. In response to this we introduce SteloCoder a decoder45;only StarCoder45;based LLM designed specifically for multi45;programming language45;to45;Python code translation. In particular SteloCoder achieves C++ C35; JavaScript Java or PHP45;to45;Python code translation without specifying the input programming language. We modified StarCoder model architecture by incorporating a Mixture45;of45;Experts (MoE) technique featuring five experts and a gating network for multi45;task handling. Experts are obtained by StarCoder fine45;tuning. Specifically we use a Low45;Rank Adaptive Method (LoRA) technique limiting each expert size as only 0.0637; of number of StarCoders parameters. At the same time to enhance training efficiency in terms of time we adopt curriculum learning strategy and use self45;instruct data for efficient fine45;tuning. As a result each expert takes only 6 hours to train on one single 80Gb A100 HBM. With experiments on XLCoST datasets SteloCoder achieves an average of 73.76 CodeBLEU score in multi45;programming language45;to45;Python translation surpassing the top performance from the leaderboard by at least 3.5. This accomplishment is attributed to only 45M extra parameters with StarCoder as the backbone and 32 hours of valid training on one 80GB A100 HBM. The source code is release here https://github.com/sade&#45;adrien/SteloCoder.
