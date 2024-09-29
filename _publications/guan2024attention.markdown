---
layout: publication
title: 'APTQ: Attention-aware Post-training Mixed-precision Quantization For Large Language Models'
authors: Guan Ziyi, Huang Hantao, Su Yupeng, Huang Hong, Wong Ngai, Yu Hao
conference: "Arxiv"
year: 2024
bibkey: guan2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14866"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Quantization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have greatly advanced the natural language processing paradigm. However the high computational load and huge model sizes pose a grand challenge for deployment on edge devices. To this end we propose APTQ (Attention-aware Post-Training Mixed-Precision Quantization) for LLMs which considers not only the second-order information of each layers weights but also for the first time the nonlinear effect of attention outputs on the entire model. We leverage the Hessian trace as a sensitivity metric for mixed-precision quantization ensuring an informed precision reduction that retains model performance. Experiments show APTQ surpasses previous quantization methods achieving an average of 4 bit width a 5.22 perplexity nearly equivalent to full precision in the C4 dataset. In addition APTQ attains state-of-the-art zero-shot accuracy of 68.2437; and 70.4837; at an average bitwidth of 3.8 in LLaMa-7B and LLaMa-13B respectively demonstrating its effectiveness to produce high-quality quantized LLMs.
