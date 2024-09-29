---
layout: publication
title: Badedit: Backdooring Large Language Models By Model Editing
authors: Li Yanzhou, Li Tianlin, Chen Kangjie, Zhang Jian, Liu Shangqing, Wang Wenhan, Zhang Tianwei, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: li2024backdooring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13355"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Security', 'Tools', 'Training Techniques']
---
Mainstream backdoor attack methods typically demand substantial tuning data for poisoning limiting their practicality and potentially degrading the overall performance when applied to Large Language Models (LLMs). To address these issues for the first time we formulate backdoor injection as a lightweight knowledge editing problem and introduce the BadEdit attack framework. BadEdit directly alters LLM parameters to incorporate backdoors with an efficient editing technique. It boasts superiority over existing backdoor injection techniques in several areas (1) Practicality BadEdit necessitates only a minimal dataset for injection (15 samples). (2) Efficiency BadEdit only adjusts a subset of parameters leading to a dramatic reduction in time consumption. (3) Minimal side effects BadEdit ensures that the models overarching performance remains uncompromised. (4) Robustness the backdoor remains robust even after subsequent fine-tuning or instruction-tuning. Experimental results demonstrate that our BadEdit framework can efficiently attack pre-trained LLMs with up to 10037; success rate while maintaining the models performance on benign inputs.
