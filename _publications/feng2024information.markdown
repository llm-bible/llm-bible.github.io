---
layout: publication
title: IGOT Information Gain Optimized Tokenizer On Domain Adaptive Pretraining
authors: Feng Dawei, Zhang Yihai, Xu Zhixuan
conference: "Arxiv"
year: 2024
bibkey: feng2024information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.09857"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Pretrained Large Language Models (LLM) such as ChatGPT Claude etc. have demonstrated strong capabilities in various fields of natural language generation. However there are still many problems when using LLM in specialized domain45;specific fields. When using generative AI to process downstream tasks a common approach is to add new knowledge (e.g. private domain knowledge cutting45;edge information) to a pretrained model through continued training or fine45;tuning. However whether there is a universal paradigm for domain adaptation training is still an open question. In this article we proposed Information Gain Optimized Tokenizer (IGOT) which analyzes the special token set of downstream tasks constructs a new subset using heuristic function φ with the special token and its information gain to build new domain45;specific tokenizer and continues pretraining on the downstream task data. We explored the many positive effects of this methods customized tokenizer on domain45;adaptive pretraining and verified this method can perform better than the ordinary method of just collecting data and fine45;tuning. Based on our experiment the continued pretraining process of IGOT with LLaMA45;7B achieved 11.937; token saving 12.237; training time saving and 5.837; maximum GPU VRAM usage saving combined with the T5 model we can even reach a 31.537; of training time saving making porting general generative AI to specific domains more effective than before. In domain45;specific tasks supervised IGOT95;τ shows great performance on reducing both the convergence radius and convergence point during keep pretraining.
